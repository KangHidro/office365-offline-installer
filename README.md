1. Download:
- Office Deployment Tool: https://www.microsoft.com/en-us/download/details.aspx?id=49117
- Extract and take only `setup.exe`
- O365 ProPlus ISO: https://officecdn.microsoft.com/db/492350F6-3A01-4F97-B9C0-C7C6DDF67D60/media/en-US/O365ProPlus2019Retail.img
- Extarct `Office` folder to same dir with `setup.exe` & `cfg.xml`
- Edit `cfg.xml`, field `SourcePath`, value is parent folder of `Office` folder

Eg:
```
C:\OfficeSetup\setup.exe
C:\OfficeSetup\cfg.xml
C:\OfficeSetup\Office\.....
```
Then `SourcePath="C:\OfficeSetup"`

2. Install: 
Open CMD, run `setup.exe /configure cfg.xml`
