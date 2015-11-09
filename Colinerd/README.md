# Plex Media Server - With Remote Share Support!


> This image is based on [limetech/plex](https://hub.docker.com/r/limetech/plex/) but adjusted to support a remote share within Plex!

## Installation
"/remotemnt" is the folder where the share will be mounted inside the container.

REMOTE_LOCATION - specify remote location like this "//remoteserver/media"

SHARE_USERNAME - specify username required to access share, use "quest" if not required

SHARE_PASSWORD - specify password, leave empty if using guest, do specify when running!

32400 is the default port used for PLEX. The best thing is to run this container in the "HOST" network mode.
To access the Plex GUI, open the webbrowser and go to http://serverip:32400/web/index.html

## License
The Plex logo, and name are copyright of Plex Inc.