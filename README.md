# Examplify Install/Update Scripts

A set of scripts to Install or update Examplify on lab devices.

ExamplifyUpdate and ExmplifyInstall scripts were copied from Examsoft's [Examplify: Lab Setup](https://support.examsoft.com/hc/en-us/articles/12000932117005-Examplify-Lab-Setup) page.

*ExamplifyInstall* is for machines that ***do not*** have Examplify installed at all.
*ExamplifyUpdate* is for machines that ***already*** have Examplify installed, but need an update.

## Instructions
1. Download the latest version of the Examplify installer .exe (3.4.6 for Windows currently)
2. Contact Examsoft Support for your .iss and .json setup files. 
3. Download the latest .zip from this repository
3. Extract the files into an empty directory titled "Examplify"
4. Add your .iss and .json files as well as the installer .exe 
5. Move ExamplifyCopy into root directory of USB drive
6. Insert USB drive into the machine you want Examplify to be installed on.
7. Left-click and then right-click on ExamplifyCopy
8. Select "Run as administrator"
9. Go to the C:\Examplify on the machine
10. Left-click and then right-click on ExamplifyInstall or ExamplifyUpdate
11. Select "Run with PowerShell"
12. Select "Yes" to allow the installer to make changes to the device.

The Examplify installer icon will appear, but will run in the background.

Once the icon disappears, Examplify is installed! 