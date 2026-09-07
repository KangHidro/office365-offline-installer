1. Download:
- Office Deployment Tool: https://www.microsoft.com/en-us/download/details.aspx?id=49117
- Extract and take only `setup.exe`
- Download O365 ProPlus ISO: https://officecdn.microsoft.com/db/492350F6-3A01-4F97-B9C0-C7C6DDF67D60/media/en-US/O365ProPlusRetail.img
- Open ISO as a drive, remember the drive label (Eg. `F:\`)
- Download this `cfg.xml`
- Edit `cfg.xml`, field `SourcePath`, value is the drive label above
- You can also edit `cfg.xml` to enable or disable Office apps you want, Autoupdate, AllowCdnFallback
- Place `cfg.xml` and `setup.exe` at a same folder

2. Install: 
- Open CMD **as Administrator**
- `cd` to the folder above (where placed `cfg.xml` and `setup.exe`)
- Run `setup.exe /configure cfg.xml`




3. ...
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Office\ClickToRun\Configuration`
