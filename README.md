# volume-notification-dunst
This script enables dunst (or any other notification daemon) to send traditional volume notifications (screenshots below).
Inspired by https://gist.github.com/sebastiencs/5d7227f388d93374cebdf72e783fbd6a


# installation
The script requires the <a href="https://github.com/snwh/faba-icon-theme.git">faba icon pack</a> to be installed (otherwise icons won't be displayed) and need some packages installed 
```
#Debian, Ubuntu, Kali
apt-get install alsa-utils libnotify-bin

#Alpine
apk add alsa-utils libnotify

#Arch Linux
pacman -S alsa-utils libnotify

#CentOS
yum install alsa-utils libnotify

#Fedora
#dnf install alsa-utils libnotify
```

# manual

```
/path/to/volume.sh up            to increase the volume

/path/to/volume.sh down          to decrease the volume

/path/to/volume.sh mute          to mute the volume
```

Or bind the desired functionality to your key combination of choice.
# screenshots
<a href="http://i.imgur.com/IKpZvez.png">
  <img src="http://imgur.com/IKpZvezl.png" />
</a>

<a href="http://i.imgur.com/JrsExYe.png">
  <img src="http://imgur.com/JrsExYel.png" />
</a>
