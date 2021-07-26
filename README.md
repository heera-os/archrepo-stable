# Archlinux Repository for Heera OS **(Stable)**

> Find the latest `-git` packages, in https://github.com/heera-os/archrepo

### Usage

Add following lines to your /etc/pacman.conf.

```
[heera]
SigLevel = Optional
Server = https://heera-os.github.io/archrepo-stable/$arch/
```

> Then to use Heera DE, install all packages of group `heera`, and run `startx /usr/bin/heera-session` (ie. if not using a window manager, like [gdm](https://wiki.archlinux.org/title/GDM))

These packages are built by Github Actions, and from the latest -git sources, hence may provide additional features as the heera os repositories are updated.

* All of these packages belong to the `heera` group

