# distbox

ONLY for Fedora Atomic Desktops (Silverblue, Kinoite, etc)

X11 and Wayland Apps work

host system survives when `sudo rm -rf / --no-preserve-root` is run in the distbox

![image](https://github.com/alexsch01/distbox/assets/5721147/93c4e810-bf76-4fde-b365-64a0140988b2)

### How To Install
```
curl -s https://raw.githubusercontent.com/alexsch01/distbox/main/install | sh
```

### Commands
install/replace your distbox - `distbox install`

run your distbox - `distbox run COMMAND`

enter your distbox (alias for distbox run bash) - `distbox enter`

stop your distbox - `distbox stop`
