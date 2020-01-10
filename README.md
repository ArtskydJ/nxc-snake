nxc-snake
=========

The classic game of Snake, now on your NXT!


## Build

### Prerequisites

- [BricxCC](http://bricxcc.sourceforge.net/) (Windows)
- An NXT
	- *Snake.nxc requires enchanced NBC/NXC firmware.*
	- SnakeTiny.nxc allows you to use the standard firmware, but it has dumb controls because it can't use the dark-gray "exit" button.
- Clone the [nxc-modules repo](https://github.com/ArtskydJ/nxc-modules) in the same directory that you cloned this repo.

### Compile to the NXT

You have a few options:

1. Open the Snake.nxc file in BricxCC, and click Download
2. Run this from the command line: `"C:\Program Files (x86)\BricxCC\nbc.exe" -s=usb -d Snake.nxc`
3. Run this from the command line: `"C:\Program Files (x86)\BricxCC\nbc.exe" -s=usb -d -sm- Snake.nxc` (for quieter output)
4. Use Sublime Text 3's build system, along with [my tutorial](https://www.josephdykstra.com/compiling-nxc-using-sublime-build)

### to do

- Split into separate files

## License

[VOL](http://veryopenlicense.com)
