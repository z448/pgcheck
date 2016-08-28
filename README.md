*update v2.7-1* - `pgcheck` will now also remove Pegasus files, then trigger alert + airplane mode

# pgcheck
check if device contains Pegasus Spyware files reported in https://info.lookout.com/rs/051-ESQ-475/images/lookout-pegasus-technical-analysis.pdf

# INSTALLATION
add Cydia repository http://load.sh/cydia/
search for pgcheck

# or 

clone this repository and use `pgcheck` as root

```bash
git clone https://github.com/z448/pgcheck
cd pgcheck/usr/bin
pgcheck i
# respring device
pgcheck
```

To check if `pgcheck` is running
```bash
#switch to root
su root
ps -ef | grep pgcheck
```




# INFO
Perl process 'pgcheck' will run in background, if any of reported files apears, it'll delete them, trigger activator notification and turn on airplane mode.

After rebooting iDevice, LaunchDaemon (/Library/LaunchDaemons/sh.load.pgcheck.plist) will start pgcheck automatically.

# GIF

![pgcheck](https://raw.githubusercontent.com/z448/pgcheck/master/pgcheck.gif)





