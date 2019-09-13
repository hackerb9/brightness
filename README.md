# brightness
Changes brightness of all connected monitors in software. This is to be used in the case where `xbacklight` fails. 
It was designed to be bound to keyboard shortcuts.

<img src="https://i.stack.imgur.com/R5wQz.png">


## Examples
    brightness 75
    brightness -5
    brightness +10

## Usage
       brightess [n] [+n] [-n]
       n       An integer from 0 to 100 specifies a brightness level.
       +n      Increase brightness by n.
       -n      Decrease brightness by n.
               No argument shows current brightness level.
## Installation

1. wget https://github.com/hackerb9/brightness/raw/master/brightness
1. chmod 755 brightness
1. sudo mv brightness /usr/local/bin/

## See also sarmad

I've also written a program called [sarmad](https://github.com/hackerb9/sarmad) which works for external monitors using the built-in brightness keys on laptops. It monitors the brightness of the internal backlight and replicates that. 
