### Prerequisites

On Ubuntu, your user needs to be in the input group to be able to
access the events.  

```
$ sudo adduser `whoami` input
```

We also need programs to parse the inputs and do various actions:

```
$ sudo apt install libinput-tools xdotool pqiv
```

A utility that's useful for controlling the screen under Wayland/Gnome:

```
https://github.com/maxwellainatchi/gnome-randr-rust
```
