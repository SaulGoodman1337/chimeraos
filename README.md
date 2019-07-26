# gamerOS: the definitive couch gaming experience

## What is it?
gamerOS is an operating system focused exclusively on a couch gaming experience. After installation, boot directly into Steam Big Picture and start playing your favorite games.

If you want Steam in your living room, you want gamerOS.


## Known Issues
See the GitHub [issues](https://github.com/gamer-os/gamer-os/issues) for a list of current limitations and bugs.


## Features

### easy to install
boot into your new gaming system within minutes (work in progress)

### minimal
only what you need to play games and nothing more

### out of the box
start gaming right away with zero configuration

### always up to date
frequent updates delivering the latest drivers and software for an optimal experience

### zero downtime updates
fully automatic updates that run in the background without disrupting gameplay ([details](https://github.com/gamer-os/frzr))

### controller first
fully controller compatible interface with no mouse or keyboard required (but you can still use a mouse and keyboard if you really want to)

### use any controller
support for Xbox 360, Xbox One, DualShock 4, Switch Pro, Steam controllers and more (compatibility varies by game)

### play any game
out of the box support for playing NES, SNES, Genesis, N64, PlayStation, Wii, Steam games and more (only Steam games are supported out of the box, emulators are pre-installed but currently require manual setup)


## Requirements
 - a wired internet connection
 - **4GB** or more RAM
 - a single **10GB** or larger dedicated storage device
 - a single connected TV or monitor with a resolution of 720p, 1080p, or 2160p


## Installation
 - [download](https://www.archlinux.org/download) and boot into the Arch Linux installer
 - make sure you are connected to the internet, consult the [Arch Linux Wiki](https://wiki.archlinux.org/index.php/Network_configuration) for help
 - download the gamerOS install script with the following command:
	`wget https://gamer-os.github.io/gamer-os/install.sh`
 - set executable permissions: `chmod +x install.sh`
 - run `./install.sh /dev/sdX` where `/dev/sdX` is the device you wish to install to; for a list of installation targets run `lsblk`
 - NOTE: if you see an error related to `fsck.overlay`, it is safe to ignore
 - run `reboot` to restart the computer after setup is complete
 - after restarting you will be presented with the SteamOS setup wizard and then Steam will start in big picture mode
 - you can open a terminal by using the keyboard combination `ctrl + alt + f2` and log in with username `gamer` and password `gamer`; switch back to big picture mode by pressing `ctrl + alt + f7`


## Discord

You can join our community [here](https://discord.gg/fyKBrv)!


## Steam
 - [group](https://steamcommunity.com/groups/gamer-os)
 - [curator](https://store.steampowered.com/curator/35483972-gamer-os)