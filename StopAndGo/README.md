Stop & Go
=========
Extended version of "WallAvoidance".
RGB LED indicates the intensity of sound: Blue (quiet) - Green - Red (Noisy).
If ambient sound exceeds "Max Strength", Robot will stop (or go - depends on the current state).

Video: https://goo.gl/photos/tmdbJKWGunph3VmC9

### Compile & Upload
```sh
$ export ARDUINO_DIR=<arduino ide dir>

$ make -f ../Makefile compile
$ make -f ../Makefile upload
```
