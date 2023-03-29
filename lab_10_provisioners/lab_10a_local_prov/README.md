Example of Local provisioner

Docs:
Shows a creation time and a destroy time local provisioner

The creation-time provisioner creates (if not existing) a subdirectory "temp" under the current directory, then writes for each instance:

Server 1: IP address is 172.31.41.116
Server 0: IP address is 172.31.26.137

Note that only a single command is allowed - thus we use ";" to join two commands

This command runs only the first time the instance is created, not when there are updates.

The destroy-time provisioner destroys the directory


