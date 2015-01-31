# Get-CurrentUsers

Script to remotely pull a list of all currently logged on users on a Windows system.  Rather than hunting for logs indicating authentication, it makes WMI calls to pull processes such as explorer.exe running under a user's context, make it much more accurate.
