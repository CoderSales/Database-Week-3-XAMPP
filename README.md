# Database-Week-3-XAMPP
Database-Week-3-XAMPP

____

From: 

mysql_error.log

in

C:\xampp\mysql\data

from XAMPP Control Panel -> MySQL -> Logs -> mysql_error.log

opens 

mysql_error.log

which has the following line:

Plugin 'Aria' registration as a STORAGE ENGINE failed

____

Google Search: [Plugin 'Aria' registration as a STORAGE ENGINE failed](https://www.google.com/search?q=Plugin+%27Aria%27+registration+as+a+STORAGE+ENGINE+failed&oq=Plugin+%27Aria%27+registration+as+a+STORAGE+ENGINE+failed&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIICAEQABgWGB4yCggCEAAYgAQYogTSAQc4NTNqMGo3qAIAsAIA&sourceid=chrome&ie=UTF-8)

____

Result: [How to fix Error: MySQL shutdown unexpectedly on Xampp due to Plugin 'Aria'](https://stackoverflow.com/questions/41170937/how-to-fix-error-mysql-shutdown-unexpectedly-on-xampp-due-to-plugin-aria)

The solution is Removing the aria_log_control file allowed MariaDB to start again. You can find this file in \xampp\mysql\data. Then restart or start xammp.

____

Google Search: [get log of files in a windows folder in cmd on windows using a command](https://www.google.com/search?q=get+log+of+files+in+a+windows+folder+in+cmd+on+windows+using+a+command&num=10&newwindow=1&sca_esv=d63eb84656ac4be5&sca_upv=1&sxsrf=ADLYWIIJZRxmbzMM9o7kDmcdm9q8vLvLag%3A1727253911946&ei=l83zZum4Oce4hbIPrYauiQM&ved=0ahUKEwip4O6e2t2IAxVHXEEAHS2DKzEQ4dUDCBA&uact=5&oq=get+log+of+files+in+a+windows+folder+in+cmd+on+windows+using+a+command&gs_lp=Egxnd3Mtd2l6LXNlcnAiRmdldCBsb2cgb2YgZmlsZXMgaW4gYSB3aW5kb3dzIGZvbGRlciBpbiBjbWQgb24gd2luZG93cyB1c2luZyBhIGNvbW1hbmRI7mRQuhBY52NwBHgBkAEAmAFqoAH2D6oBBDM2LjG4AQPIAQD4AQGYAiCgAt0MwgIKEAAYsAMY1gQYR8ICCBAAGIAEGKIEwgIIECEYoAEYwwTCAgoQIRigARjDBBgKwgIFECEYoAHCAgcQIRigARgKmAMAiAYBkAYIkgcCMzKgB918&sclient=gws-wiz-serp)

____

Result: [How to logs result to file AND display when using W10 CMD.EXE? [duplicate]](https://superuser.com/questions/1721284/how-to-logs-result-to-file-and-display-when-using-w10-cmd-exe)

```bash
dir > a.txt | type a.txt
```

____
