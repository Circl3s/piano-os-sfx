# piano-os-sfx
Tired of the _freedesktop_ sound effects? The distro you're using has some distracting noises and you shit yourself every time you get a ping from Discord? Maybe you're on Windows and you want a breath of fresh air? Then feel free to use my hardly mediocre SFX pack! **Featuring:**
* Piano

And that's about it!

_Note: this is extremely WIP, as this is a first for me. More sounds to come; I will expand the installation section as I learn to change sounds on different OSs; if you know how to change sounds on your OS, feel free to contribute! All feedback welcome._
## Installation
### Deepin
Deepin doesn't support changing sound themes, so you have to trick it into thinking that this is the Deepin sound theme. Also, the directory we're working with **belongs to root**, so everything you see below must be done as root - either open the terminal as root, add `sudo` where applicable, log in as root, or do whatever else might come to mind...

**1. Clone this repo into /usr/share/sounds/piano-os-sfx/** 

```
cd /usr/share/sounds/
git clone https://github.com/maak4422/piano-os-sfx.git/
```

**2. Edit the _/piano-os-sfx/index.theme_, so the second line reads**
```
Name=Deepin
```
**3. Change the folder names around**

Rename the _/sounds/deepin/_ folder to something like _/sounds/deepin-old/_, and the _/sounds/piano-os-sfx/_ folder to _/sounds/deepin/_
```
mv /usr/share/sounds/deepin/ /usr/share/sounds/deepin-old/
mv /usr/share/sounds/piano-os-sfx/ /usr/share/sounds/deepin/
```

**4. Reboot your computer, and after a while you should hear my awesome log in sound!**
