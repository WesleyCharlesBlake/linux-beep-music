# A collection of Beep music for Linux

## Available songs:
* [Mario Brothers Theme Song](mario-beep.sh)
* [Da Rude - Sand Storm](da-rude.sh)

## Debian / Ubuntu

You will need to load the pcspkr module

```
sudo modprobe pcspkr
```

And remove the blacklist for the module if its blacklisted:

```
/etc/modprobe.d/blacklist.conf
blacklist pcspkr #remove this line
```

Then if you are using alsamixer, you need to pump the volume on the Beep channel

To get the alsmixer util up, run the following from a terminal

```
alsamixer
```

## But Why ??
Initially, I used these scripts to play nice beep music on my Mikrotik router boards when the booted up etc. But I guess your use case be as wide as your imagination will allow
