# Retro Pie

This is a project to regulate fanspeed on the retropie I made. The fan is only 5V and is rather loud, so with these python scripts the fan can change speed as the temperature increases and decreases on the CPU.

## crontab -e
(look at readme for Oswald repo for more info)
@reboot su -s /bin/sh root -c 'cd /home/pi/retropie && git pull origin master && python3 fan_ctrl.py'
