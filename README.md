custom-role/service
==========================

Overview
--------
The `service` role enables users to configure services on the target machines.
This role can be used to:

- Check whether a service is running on a remote host.
- Enable a service on a remote host.
- Check if a package is installed on a remote host.
- Install a package on a remote host.


Introduction
------------
This role was created by Mark Hillis (Red Hat Solution Architect) for use with Red Hat Satellite.   
The intended use is to ensure a package is installed and that the service is running and enabled. 


Variables
---------
*service_name* - Define the name of the service that should be running/enabled on the remote host.
*package_name* - Define the name of the package that shoudl be installed on the remote hosts. 

Examples of Variables
---------------------

    vars:
    - service_name: httpd
    - package_name: httpd.service

