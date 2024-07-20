# ENIGMA-DialogModule-Demo
ENIGMA DialogModule Demo GM81 Project File

Only works with my fork of enigma: https://github.com/time-killer-games/stigma-dev

![DialogModule](https://github.com/time-killer-games/ENIGMA-DialogModule-Demo/raw/main/DialogModule.gif "DialogModule")

Example GM81 Project must build with the SDL Platform on Windows/Mac, otherwise use X11 Platform.

Demo Windows EXE needs the entire ZIP to be extracted, with nothing deleted or moved, before run.

Demo Mac App needs this run in the Terminal App after extracting the ZIP to the Downloads folder:

```
xattr -d -r com.apple.quarantine $HOME/*/DialogModule
```

Demo AppImage needs the following dependencies installed before it can run on Debian-based Linux:

```
sudo apt install libfuse-dev libglew-dev zenity
```
