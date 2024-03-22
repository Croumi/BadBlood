BadBlood
========
BadBlood fills a Microsoft Active Directory Domain with a structure and thousands of objects. The output of the tool is a domain similar to a domain in the real world.  After BadBlood is ran on a domain, security analysts and engineers can practice using tools to gain an understanding and prescribe to securing Active Directory. Each time this tool runs, it produces different results.  The domain, users, groups, computers and permissions are different. Every. Single. Time.


## Installation

Requirements:
- Domain Admin and Schema Admin permissions
- Active Directory Powershell Installed

Running On Windows:
```
Set-ExecutionPolicy bypass
.\Invoke-BadBlood.ps1 -SkipLapsInstall
```
