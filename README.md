# FumOS-bootc &nbsp; [![bluebuild build badge](https://github.com/fumofumoenjoyer/test-os/actions/workflows/build.yml/badge.svg)](https://github.com/fumofumoenjoyer/test-os/actions/workflows/build.yml)

WIP Linux distribution based on bazzite-gnome and the bluebuild template

## Features
MangoWC
DMS Shell
Brew
Podman
Distrobox

## Installation
Install bazzite with the gnome desktop environment amd or(nvidia is not supported yet)
once you log in clone this repo and move everything inside ```files/system/usr/etc/skel``` to your home directory
then rebase to FumOS
```
sudo bootc switch ghcr.io/fumofumoenjoyer/fumos:latest
```
then reboot, when you get to the login screen clck your user then the "settings" icon and select mango, then log in
