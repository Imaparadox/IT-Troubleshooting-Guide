# IT-Troubleshooting-Guide
This is a comprehensive list of different console commands and step-by-step instructions for resolving general technical issues.

## To add a new user to an Azure Active Directory
* Right-click on the user's account then click: 'reset password'.
### Comand sequence in PowerShell:
1. `import-module activeirectory`
1. `get-command new-aduser`
1. `new-aduser [insert name]`
### Commands to confirm the device:
1. `whoami`
1. `whoami /fqdn`
## To enable a new user to an Azure Active Directory
* Right-click on the user's account then click: 'enable the account'.
