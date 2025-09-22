# Build log

## 🎬 Introduction
I decided to build the Raspberry Pi Magic Mirror as a project during the summer holidays as I didn't have a mirror in my room, and desired a unique one. This magic mirror was perfect for usage, while displaying other details in a productive way also.

## 🔩 Assembly of Hardware
### Mirror and Monitor
I found an old monitor in my house, which to my surprise still worked and had HDMI ports, which I used rather than buying another monitor. I custom ordered a 2 way mirror from Ebay, which arrived the perfect size, which I had specified slightly smaller so it would fit inside the monitor. To secure the mirror onto the monitor, I used sticky back white tape which I ordered from Amazon. This worked well, although it was hard to keep stick the tape down neatly, so ended up looking a little scruffy. However, secured the mirror well, and covered the broken parts of my monitor.

### Raspberry Pi
My Raspberry Pi came with the power supply, so luckily I didn't have the worry about that. However, I had to deal with the challenge of a dead SD Disk, which took me 2 different devices and a lot of irritation to realise. Luckily, my dad had a spare, old SD Disk which he used for photography, and lent me it. I then had a little trouble etching the Raspberry Pi software onto the disk with the balenaEtcher, recieving many errors, but I switched to the Raspberry Pi Imager and flashed just fine.

## 💻 Assembly of Software
Once I had the Raspberry Pi software running, I installed Node.js, npm and nvm. I then followed the instructions from the [MagicMirror² repository](https://github.com/MagicMirrorOrg/MagicMirror) to clone it, and install dependencies. From there, I was able to run MagicMirror with default modules. Afterwards, I visited the [MagicMirror² 3rd Party Modules List](https://modules.magicmirror.builders) and followed the given instructions to install another three custom modules to my Magic Mirror.
