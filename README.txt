Python program that runs in background and it doesn't let users browse certain website during working hours.

To run program:
1.Open hosts file(/etc/hosts in ubuntu) and append websit   e names in it.
2.Run script using crontab. 
  Open crontab using command "sudo cron -e".
  Append "@reboot python `path of script`" in crontab.  
