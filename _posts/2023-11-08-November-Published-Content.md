## This is my first blog post
Summary of Published Content for November 2023

This month i decided to sanitize and publish some modules i have been using internally.

- **psBlackberryUEM**: A module for interacting with the Blackberry UEM API.

 - Its not really my primary job to interact with this service, but i run our on-boarding and off-boarding processes and wanted to be able to integrate this app into those. That led to a full blown module to cover the entire API that our internal team that manages the app now uses.
 - [Github](https://github.com/hematic/psBlackberryUEM/tree/1.0.20)
 - [psBlackberryUEM - PSGallery](https://www.powershellgallery.com/packages/psBlackberryUEM/)

- **psTroubleshootWinRM**: A module for gathering concise information about machines that have broken psRemoting.
 - I also got absolutely sick of troubleshooting WinRM errors in my environment and having to try to figure out what certain servers that fail might have in common so i wrote this. It can be run against a batch of servers to return you a nice little object with a bunch of test data about winRM.
 - [Github](https://github.com/hematic/psTroubleshootWinRM)
 - [psTroubleshootWinRM - PSGallery](https://www.powershellgallery.com/packages/psTroubleshootWinRM)


- **psConnecttoExchange**: A module for allowing users to easily run Exchange commands on non-exchange machines.
 - This is a favorite in our environment. Many automated processes run on machines that dont have access to an exchange console and this allows for an easy remote connection to process those commands seamlessly.
 - [Github](https://github.com/hematic/psConnecttoExchange)
 - [psTroubleshootWinRM - PSGallery](https://www.powershellgallery.com/packages/psConnecttoExchange/1.2.5)

- **psACL**: This module allows for control over Access Control Lists in Windows without having to use ICACLs.'
 - [Github](https://github.com/hematic/psACL)
 - [psACL - PSGallery](https://www.powershellgallery.com/packages/psACL)

I also published a few other repositories that aren't modules.

- **Powershell-Reports**: A repository for publishing of a few random PowerShell reports.
 - Accounts Never Logged On.
 - Active Directory General Information Report
 - AD Token Size Report
 - Expiring Accounts
 - Windows Defender Status Report
 - Server Report
 - [Github - PowerShell Reports](https://github.com/hematic/Powershell-Reports)

- **User-Onboarding**: A repository for a sanitized version of our user onboarding process.

 - [Github - User Onboarding](https://github.com/hematic/User-Onboarding)
