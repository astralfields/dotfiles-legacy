# "Ocean" theme for i3-gaps

These are most of my configs and other files I once used for my laptop's rice. I don't use it anymore but I'm keeping it for others to enjoy.

Here's what it looks like:

![example screenshot](http://i.imgur.com/3GStKHT.png)

There are more images in [this album](http://imgur.com/a/WkvTg). The **wallpaper** is included.

For these settings to work you need:

- i3-gaps
- compton
- Xfce (optional)
- Firefox with Stylish addon (optional)

Usually, the i3 config file is at *~/.i3/config* and compton's is at *~/.config/compton.conf*.

Install TinyCSS-edit as a userstyle with Stylish. Chromium does not support this, sadly.

**When using Xfce** (I use it for the panel and settings menu), use its session manager to set xfdesktop and xfwm4 to never restart (but keep xfsettingsd and xfce4-panel), have i3 and compton start on boot, save the session, logout and login. Install the "Numix-DarkBlue" system theme (available on AUR as *numix-themes-darkblue*) and "Numix Circle" icon theme (available on AUR as *numix-circle-icon-theme-git*) for graphical apps.

**When not using Xfce**, configure i3bar or some other bar of your choosing. Or do whatever. Your choice.

The **terminal color scheme** is called **Smyck**. You can find it on [its homepage](http://color.smyck.org/) or [on GitHub](https://github.com/hukl/Smyck-Color-Scheme/).
