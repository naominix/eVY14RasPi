eVY14RasPi
==========

eVY1 Scratch on Raspberry Pi for Pokemiku NSX-39 Installer

## Installation

Install eVY1 Scratch.

### Network Online

```
$ cd /home/pi
$ curl https://naominix.github.io/pokemikuinstall.sh | sh
```

### Network Offline

Download the Zip file from GitHub.

https://github.com/naominix/eVY14RasPi/archive/master.zip

```
$ cd /home/pi
$ unzip master.zip
$ cd eVY14RasPi-master
$ cat localinstall.sh | sh
```

Overwrite so.MIDIPlugin file.

## Getting Started

1. Boot Raspberry Pi
2. After the LXDE Desktop displayed, Connect NSX-39(Pocket Miku).
3. Double click eVY1 Scratch icon on desktop shortcut to start eVY1 Scratch
4. Click Sound category, Right Click "Play Note Block" and Select MIDI device.


## Special Thanks

eVY1 Scratch : Kazuhiro Abe

Patched so.MIDIPlugin : Manabu Sugiura
