boot2docker-launch
==================

OS X launch plist to launch boot2docker at system startup

Installation
============

```bash
  curl -L -O ~/Library/LaunchAgents/io.boot2docker.boot2docker.plist https://github.com/gilgamez/boot2docker-launch/raw/master/io.boot2docker.boot2docker.plist
  launchctl load ~/Library/LaunchAgents/io.boot2docker.boot2docker.plist
```

Check /usr/local/var/log/boot2docker.log if all went well.
