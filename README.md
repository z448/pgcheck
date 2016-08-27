# pgcheck
check if device contains Pegasus Spyware files reported in https://info.lookout.com/rs/051-ESQ-475/images/lookout-pegasus-technical-analysis.pdf

# Installation
add Cydia repository http://load.sh/cydia/
search for pgcheck

Device will respring and perl process 'pgcheck' will run in background, if any of reported files apears, it'll trigger activator notification and turn on airplane mode.

After rebooting iDevice, LaunchDaemon (/Library/LaunchDaemons/sh.load.pgcheck.plist) will start pgcheck automatically.







