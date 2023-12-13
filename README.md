# .dotfiles

Currently not all files ;D

My personal system is endeavourOS, so all next commands is for arch-based systems

### The needed packages

```
yay -S picom-git polybar-git xmousepasteblock-git nerd-fonts-git 
```

```
sudo pacman -S alacritty
```

### Useful apps

```
yay -S telegram-desktop-bin
```

## Additional

Also I like natural scroll, it can be set up by adding `Option "NaturalScrolling" "true"` in `/usr/share/X11/xorg.conf.d/30-touchpad.conf`

```
sudo nano /usr/share/X11/xorg.conf.d/30-touchpad.conf
```

It should look like this:
>
Section "InputClass"
    Identifier "devname"
    Driver "libinput"
    Option "Tapping" "on"
    Option "NaturalScrolling" "true"
EndSection
>

