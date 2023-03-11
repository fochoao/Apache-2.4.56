###Apache 2.4.56 with PHP

## Drop into C:\ both folders.

## Issue this command as administrator: sc.exe create Apache24 binPath='"C:\Apache24\bin\httpd.exe" -k runservice'

## This should create a service named Apache24, stop it and start it, or restart it, whenenver You change configuration.
