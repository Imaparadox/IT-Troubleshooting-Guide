**# IT-Troubleshooting-Guide**
This is a comprehensive list of different console commands and step-by-step instructions for resolving general technical issues.

## To add a new user to an Azure Active Directory
* Right-click on the user's account then click: 'reset password'.
### Comand sequence in PowerShell:
1. 'import-module activeirectory'
2. 'get-command new-aduser'
3. 'new-aduser [insert name]'
4. 'whoami'
5 'whoami /fqdn'
## To enable new user to an Azure Active Directory
* Right-click on the user's account then click: 'nable the account'.
