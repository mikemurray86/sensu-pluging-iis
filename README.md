# sensu-plugins-iis
A collection of IIS utilities for the sensu monitoring framework 

## checks
Each check uses a wmi class to check if everything is running as expected. 

by default all resources are checked. If only a single resource needs to be checked then you can specify the name of the resource and only that one will be checked. check the source for parameter names. 

There are checks for the following:
- AppPool status
- Site status