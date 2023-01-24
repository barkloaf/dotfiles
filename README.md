<p align="center">
    <img src="https://i.barkloaf.com/DaESwow0t.png">
</p>

# <p align="center">barkloaf's dotfiles</p>

<p align="center">
    <span>my personal setup for arch linux featuring the <a href="https://nordtheme.com">nord color scheme</a>, bspwm, picom, polybar, and more!</span>
</p>
<br />

## Overview
<table>
    <thead">
        <tr>
            <th>Component</th>
            <th>Software</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Display server</td>
            <td><a href="https://x.org">Xorg</a></td>
        </tr>
        <tr>
            <td>Window manager</td>
            <td><a href="https://github.com/baskerville/bspwm">bspwm</a></td>
        </tr>
        <tr>
            <td>Compositor</td>
            <td><a href="https://github.com/jonaburg/picom">picom-jonaburg</a></td>
        </tr>
        <tr>
            <td>Bar</td>
            <td><a href="https://github.com/polybar/polybar">polybar</a></td>
        </tr>
        <tr>
            <td>Application launcher</td>
            <td><a href="https://github.com/davatorium/rofi">rofi</a></td>
        </tr>
        <tr>
            <td>Notification daemon</td>
            <td><a href="https://github.com/dunst-project/dunst">dunst</a></td>
        </tr>
        <tr>
            <td>GTK and icons theme</td>
            <td><a href="https://github.com/archcraft-os">Archcraft Nordic</a></td>
        </tr>
        <tr>
            <td>Font</td>
            <td><a href="https://design.ubuntu.com/font/">Ubuntu</a></td>
        </tr>
        <tr>
            <td>Cursor</td>
            <td><a href="https://kver.wordpress.com/2015/01/09/curses-i-mean-cursors/">Breeze snow</a></td>
        </tr>
        <tr>
            <td>Screenshot tool</td>
            <td><a href="https://github.com/flameshot-org/flameshot">Flameshot</a> (uploaded to a <a href="https://github.com/TannerReynolds/ShareX-Upload-Server">ShareS</a> server)</td>
        </tr>
        <tr>
            <td>Terminal</td>
            <td><a href="https://github.com/kovidgoyal/kitty">kitty</a></td>
        </tr>
        <tr>
            <td>Shell</td>
            <td><a href="https://www.zsh.org/">Z shell</a></td>
        </tr>
    </tbody>
</table>

## Mentioned packages and files
All packages are in the official Arch repositories or the Arch User Repository as named unless otherwise linked
<br />
<table>
    <thead>
        <tr>
            <th>Package / File</th>
            <th>Dependents</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/bspwm/autostart"><code>.config/bspwm/autostart</code></a></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/bspwm/bspwmrc"><code>.config/bspwm/bspwmrc</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/picom/opacity-rules"><code>.config/picom/opacity-rules</code></a></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/bspwm/bspwmrc"><code>.config/bspwm/bspwmrc</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/polybar/colors"><code>.config/polybar/colors</code></a></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/polybar/config"><code>.config/polybar/config</code></a></li>
                </ul>
            </td>
        </tr>
        </tr>
            <td><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/polybar/package-updates"><code>.config/polybar/package-updates</code></a></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/polybar/config"><code>.config/polybar/config</code></a></li>
                </ul>
            </td>
        </tr>
        </tr>
            <td><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/rofi/themes/rounded-nord-dark.rasi"><code>.config/rofi/themes/rounded-nord-dark.rasi</code></a></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/rofi/config.rasi"><code>.config/rofi/config.rasi</code></a></li>
                </ul>
            </td>
        </tr>
        </tr>
            <td><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/rofi/symbols.txt"><code>.config/rofi/symbols.txt</code></a></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.local/bin/rofi-unicode-menu"><code>.local/bin/rofi-unicode-menu</code></a></li>
                </ul>
            </td>
        </tr>
        </tr>
            <td><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/shareS/shareS.conf"><code>.config/shareS/shareS.conf</code></a></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.local/bin/shareS"><code>.local/bin/shareS</code></a></li>
                </ul>
            </td>
        </tr>
        </tr>
            <td><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/shareS/urls"><code>.config/shareS/urls</code></a></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.local/bin/shareS"><code>.local/bin/shareS</code></a></li>
                </ul>
            </td>
        </tr>
        </tr>
            <td><a href="https://github.com/barkloaf/dotfiles/blob/main/.local/bin/rofi-power-menu"><code>.local/bin/rofi-power-menu</code></a></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/sxhkd/sxhkdrc"><code>.config/sxhkd/sxhkdrc</code></a></li>
                </ul>
            </td>
        </tr>
        </tr>
            <td><a href="https://github.com/barkloaf/dotfiles/blob/main/.local/bin/rofi-unicode-menu"><code>.local/bin/rofi-unicode-menu</code></a></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/sxhkd/sxhkdrc"><code>.config/sxhkd/sxhkdrc</code></a></li>
                </ul>
            </td>
        </tr>
        </tr>
            <td><a href="https://github.com/barkloaf/dotfiles/blob/main/.local/bin/rofi-wifi-menu"><code>.local/bin/rofi-wifi-menu</code></a></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/sxhkd/sxhkdrc"><code>.config/sxhkd/sxhkdrc</code></a></li>
                </ul>
            </td>
        </tr>
        </tr>
            <td><a href="https://github.com/barkloaf/dotfiles/blob/main/.local/bin/shareS"><code>.local/bin/shareS</code></a></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/sxhkd/sxhkdrc"><code>.config/sxhkd/sxhkdrc</code></a></li>
                </ul>
            </td>
        </tr>
        </tr>
            <td><a href="https://github.com/barkloaf/dotfiles/blob/main/.local/bin/winmask"><code>.local/bin/winmask</code></a></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/sxhkd/sxhkdrc"><code>.config/sxhkd/sxhkdrc</code></a></li>
                </ul>
            </td>
        </tr>
        </tr>
            <td><a href="https://github.com/barkloaf/dotfiles/blob/main/.local/share/background.png"><code>.local/share/background.png</code></a></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/bspwm/bspwmrc"><code>.config/bspwm/bspwmrc</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><a href="https://github.com/archcraft-os/pkgs/tree/main/x86_64"><code>archcraft-gtk-theme-nordic</code></a></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/gtk-3.0/settings.ini"><code>.config/gtk-3.0/settings.ini</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code><a href="https://github.com/archcraft-os/pkgs/tree/main/x86_64">archcraft-icons-nordic</a</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/gtk-3.0/settings.ini"><code>.config/gtk-3.0/settings.ini</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>betterlockscreen</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/betterlockscreenrc"><code>.config/betterlockscreenrc</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/sxhkd/sxhkdrc"><code>.config/sxhkd/sxhkdrc</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>breeze-snow-cursor-theme</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/gtk-3.0/settings.ini"><code>.config/gtk-3.0/settings.ini</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>bspwm</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/bspwm/bspwmrc"><code>.config/bspwm/bspwmrc</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/polybar/config"><code>.config/polybar/config</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/sxhkd/sxhkdrc"><code>.config/sxhkd/sxhkdrc</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.local/bin/winmask"><code>.local/bin/winmask</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>dunst</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/bspwm/bspwmrc"><code>.config/bspwm/bspwmrc</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/dunst/dunstrc"><code>.config/dunst/dunstrc</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>easyeffects</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.xprofile"><code>.xprofile</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>feh</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/betterlockscreenrc"><code>.config/betterlockscreenrc</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/bspwm/bspwmrc"><code>.config/bspwm/bspwmrc</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>flameshot</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/bspwm/bspwmrc"><code>.config/bspwm/bspwmrc</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.local/bin/shareS"><code>.local/bin/shareS</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>gnome-keyring</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/bspwm/bspwmrc"><code>.config/bspwm/bspwmrc</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>gtk2</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.xprofile"><code>.xprofile</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>gtk3</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/gtk-3.0/settings.ini"><code>.config/gtk-3.0/settings.ini</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.xprofile"><code>.xprofile</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>kitty</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/kitty/kitty.conf"><code>.config/kitty/kitty.conf</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/sxhkd/sxhkdrc"><code>.config/sxhkd/sxhkdrc</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.zshrc"><code>.zshrc</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>ksuperkey</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.xprofile"><code>.xprofile</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>neofetch</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/neofetch/config.conf"><code>.config/neofetch/config.conf</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>networkmanager</code> (or, more preferrably, <code>networkmanager-iwd</code>)</td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/polybar/config"><code>.config/polybar/config</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.local/bin/rofi-wifi-menu"><code>.local/bin/rofi-wifi-menu</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>network-manager-applet</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.xprofile"><code>.xprofile</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>numlockx</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.xprofile"><code>.xprofile</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>paru</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/paru/paru.conf"><code>.config/paru/paru.conf</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/polybar/package-updates"><code>.config/polybar/package-updates</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>picom-jonaburg-git</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/bspwm/bspwmrc"><code>.config/bspwm/bspwmrc</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/picom/picom.conf"><code>.config/picom/picom.conf</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>pipewire-pulse</code> (enable the <code>pipewire-pulse.service</code> systemd <b>user</b> unit)</td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/polybar/config"><code>.config/polybar/config</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>polkit-gnome</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.xprofile"><code>.xprofile</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>polybar</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/bspwm/bspwmrc"><code>.config/bspwm/bspwmrc</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/polybar/config"><code>.config/polybar/config</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>polybar-spotify-module</code> (enable the <code>spotify-listener.service</code> systemd <b>user</b> unit)</td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/polybar/config"><code>.config/polybar/config</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>qt4</code> (not required or recommended to install unless necesary, but dependents are recommended regardless)</td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/Trolltech.conf"><code>.config/Trolltech.conf</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>qt5-styleplugins</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.xprofile"><code>.xprofile</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>qt6gtk2</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.xprofile"><code>.xprofile</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>rofi</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/bspwm/bspwmrc"><code>.config/bspwm/bspwmrc</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/rofi/config.rasi"><code>.config/rofi/config.rasi</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/sxhkd/sxhkdrc"><code>.config/sxhkd/sxhkdrc</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.local/bin/rofi-power-menu"><code>.local/bin/rofi-power-menu</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.local/bin/rofi-unicode-menu"><code>.local/bin/rofi-unicode-menu</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.local/bin/rofi-wifi-menu"><code>.local/bin/rofi-wifi-menu</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.local/bin/shareS"><code>.local/bin/shareS</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>rofimoji</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/sxhkd/sxhkdrc"><code>.config/sxhkd/sxhkdrc</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>spotify</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/polybar/config"><code>.config/polybar/config</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>sxhkd</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/bspwm/bspwmrc"><code>.config/bspwm/bspwmrc</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/sxhkd/sxhkdrc"><code>.config/sxhkd/sxhkdrc</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>ttf-ubuntu-font-family</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/betterlockscreenrc"><code>.config/betterlockscreenrc</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/dunst/dunstrc"><code>.config/dunst/dunstrc</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/gtk-3.0/settings.ini"><code>.config/gtk-3.0/settings.ini</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/kitty/kitty.conf"><code>.config/kitty/kitty.conf</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/neofetch/config.conf"><code>.config/neofetch/config.conf</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/polybar/config"><code>.config/polybar/config</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/rofi/config.rasi"><code>.config/rofi/config.rasi</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.local/bin/rofi-wifi-menu"><code>.local/bin/rofi-wifi-menu</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>ttf-ubuntu-mono-nerd</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/polybar/config"><code>.config/polybar/config</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>ttf-ubuntu-nerd</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.config/polybar/config"><code>.config/polybar/config</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>xclip</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.local/bin/shareS"><code>.local/bin/shareS</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>xdg-desktop-portal</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.xprofile"><code>.xprofile</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>xdg-desktop-portal-kde</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.xprofile"><code>.xprofile</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>xdg-desktop-portal-gtk</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.xprofile"><code>.xprofile</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>xdotool</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.local/bin/rofi-unicode-menu"><code>.local/bin/rofi-unicode-menu</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>zsh</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.local/bin/histfix"><code>.local/bin/histfix</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.local/bin/rofi-unicode-menu"><code>.local/bin/rofi-unicode-menu</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.local/bin/shareS"><code>.local/bin/shareS</code></a></li>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.zshrc"><code>.zshrc</code></a></li>
                </ul>
            </td>
        </tr>
        <tr>
            <td><code>zsh-syntax-highlighting</code></td>
            <td>
                <ul>
                    <li><a href="https://github.com/barkloaf/dotfiles/blob/main/.zshrc"><code>.zshrc</code></a></li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>
<br />

## Further recommendations
All packages are in the official Arch repositories or the Arch User Repository as named unless otherwise linked
* `baobab`: GTK-based directory tree analyzer
* `blueman`: GTK-based Bluetooth manager
    * `bluez-tools`: CLI tools for Bluetooth management
* `code`: Open source build of Visual Studio Code (vscode) editor
    * `code-features`: Unblocks some features in `code`
    * `code-marketplace`: Enables the marketplace in `code`
        * https://marketplace.visualstudio.com/items?itemName=arcticicestudio.nord-visual-studio-code: Nord theme for Visual Studio Code
* `gnome-calculator`: GTK-based calculator
* `gtk2fontsel`: GTK-based font preview tool
* `lightdm`: Display manager. I don't actually <i>recommend</i> `lightdm` because it breaks often, but unfortunately it is very customizable
    * `accountsservice`: D-Bus interface for user account query and manipulation. Can be used by `lightdm` to gather information such as profile picture, etc.
    * `lightdm-webkit2-greeter`: Webkit2-based greeter for `lightdm`
        * https://github.com/AlphaNecron/lightdm-gab-nord: Nord theme for `lightdm-webkit2-greeter`
            * Potentially working on my own fork
* `ly`: Alternate, TUI-based display manager. Cool if you can get it to work (I didn't) and pair it with `mkinitcpio-colors-git`
* `lxappearance-gtk3`: GTK-based theme, font, icon, cursor, etc. switcher
* `mkinitcpio-colors-git`: mkinitcpio hook to set VT console colors (such as to Nord colors) during early userspace
* `nm-connection-editor`: GTK-based NetworkManager connection editor
* `noto-fonts`: Google Noto TTF fonts, provides a base font set
    * `noto-fonts-cjk`: Google Noto Chinese-Japanese-Korean TTF fonts
* `pipewire`: Low-latency audio/video router and processor, better than PulseAudio. This package is for Pipewire clients specifically
    * `pavucontrol`: GTK-based PulseAudio volume control, for use with `pipewire-pulse`
    * `pipewire-alsa`: Pipewire for ALSA clients
    * `pipewire-jack`: Pipewire for JACK clients
* `seahorse`: GTK-based application for managing `gnome-keyring`, PGP keys, and SSH keys
* `spicetify-cli`: Command-line tool to customize Spotify client
    * `spicetify-themes-git`: Contains the **Dribbblish** theme and **nord-dark** color scheme
* `thunar`: GTK-based file manager
    * `ffmpegthumbnailer`: Lightweight video thumbnailer that can be used by `thunar`
    * `gvfs`: Provides trash support, mounting removable media, and remote filesystems in `thunar`
        * `gvfs-mtp`: MTP backend for `gvfs`
    * `thunar-archive-plugin`: Allows you to create and extract archive files using contextual menu items in `thunar`
    * `thunar-media-tags-plugin`: Allows you to view and editdetailed information about media files in `thunar`
    * `tumbler`: Generates thumbnails that can be used by `thunar`
* `ttf-twemoji`: Provides the Twitter emoji set, the best emoji set
* `viewnior`: Simple, fast and elegant GTK-based image viewer program
* `xarchiver`: GTK-based frontend to various command line archivers