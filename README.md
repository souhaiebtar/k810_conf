# logitech k810 fn switcher for linux
## How to compile
* `git clone https://github.com/souhaiebtar/k810_conf`
* `cd k810_conf`
* `gcc -o k810-conf k810_conf.c` (some error will be thrown)

## How to run

* `sudo mv k810-conf /usr/local/bin`
*  `sudo k810-conf -d /dev/`grep -H "Logitech K810" /sys/class/hidraw/hidraw*/device/uevent | cut -d/ -f 5` -f on`  or 
` sudo k810-conf -d /dev/`grep -H "Logitech K810" /sys/class/hidraw/hidraw*/device/uevent | cut -d/ -f 5` -f off`

## Credits 
http://www.trial-n-error.de/posts/2012/12/31/logitech-k810-keyboard-configurator
Mario Scholz's Logitech K810 configurator - Used for RPM packaging

## Tested and working on ubuntu 18.04
