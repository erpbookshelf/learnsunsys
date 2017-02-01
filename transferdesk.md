## Scheduling Transfer Desk Data Export
1. Create an Export profile, selecting the type of records to export
2. Create an Automation profile, entering the filename for output
3. Using Windows Task Manager, schedule the automation profile execution as follows:
```<SunDir>\SSC\bin\AutomationDesk.exe -a <automation_profile> -n -u <username> -x <password>```
