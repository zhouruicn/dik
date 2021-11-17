# dik
"Disable my Internal Keyboard" (dik) uses evtest to grab your internal keyboard into test mode, thereby stopping it from taking input. This is useful when you're running a Wayland laptop and want to place your keyboard on the internal one.

Tested on Fedora 35

## Dependencies
+ evtest

## Usage
Make the script executable.
```
chmod +x /path/to/dik
```
Disable the internal keyboard.
```
/path/to/dik
```
Re-enable the internal keyboard
```
/path/to/dik --stop
```

## Install
```
cp /path/to/dik /usr/bin
chmod +x /usr/bin/dik
```
to uninstall
```
rm /usr/bin/dik
```

## Acknowledgement
https://unix.stackexchange.com/a/382225
