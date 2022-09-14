```crontab -e``` to edit the current user's crontab and have the changes take effect
```@reboot``` to schedule a job to run every time the system boots
```m h dom mon dow /path/to/command >/dev/null 2>&1``` to suppress automatic emails upon completion of the job