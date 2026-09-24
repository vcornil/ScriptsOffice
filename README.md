# ScriptsOffice
Some useful office (Excel) Scripts

Office Scripts require a Business or Education subscription, such as:

Microsoft 365 Business Standard / Premium

Microsoft 365 Apps for Enterprise

Office 365 E1 / E3 / E5

A3 / A5

F3

Personal and Family subscriptions do not fully support Office Scripts, even if you joined the Insider program.

## 🚀 How to actually use a downloaded script again
You must import it into Excel for the Web:

Open Excel Online

Go to Automate → All Scripts

Click Import

Select your .osts file

The script appears in Excel Online and is stored in OneDrive

Only then will Excel Desktop be able to run it — but only via the Automate tab, which still connects to the cloud.


Store them under:

  %USERPROFILE%\Documents\Office Scripts


## File storage

Office Scripts are stored in your OneDrive by default. The .osts files are found in the /Documents/Office Scripts/ folder. Any edits made to these .osts files, such as renaming or deleting files, will be reflected in the Code Editor and Script Gallery. Excel only recognizes and runs a script if it's in your OneDrive folder, a Sharepoint folder, or shared with the workbook. This means Excel needs internet connectivity to access Office Scripts.

## Note

For customers with personal and family subscriptions, your Office Scripts are moving from local storage to OneDrive. The legacy script storage location for personal and family subscriptions is the following folder in your local Office cache: %LOCALAPPDATA%\Microsoft\Office\16.0\Wef\.

New scripts are saved in your OneDrive, and any existing locally stored scripts will be moved to your OneDrive automatically.


https://learn.microsoft.com/en-us/office/dev/scripts/overview/script-storage?tabs=business
