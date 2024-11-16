<h1 align="center"> :evergreen_tree: Hi there, I'm Barmaley :evergreen_tree: </h1>
<h5 align="center"> install and config arch linux  + bspwm + polybar </h5>

<!-- INFORMATION -->
<h1 align="left"> :computer: system parameters </h1> 

<!-- добавить показатели системы -->
<!-- <img src="demonstration/1.png" alt="rice" align="right" width="500px"> -->

</br>

 - OS: [**`Arch Linux`**](https://archlinux.org/)
 - Terminal: [**`Kitty`**](https://sw.kovidgoyal.net/kitty/)
 - WM: [**`BSPWM`**](https://github.com/baskerville/bspwm)
 - Bar: [**`Polybar`**](https://github.com/polybar/polybar)
 - Compositor: [**`Picom`**](https://github.com/yshui/picom)
 - App Launcher: [**`Rofi`**](https://github.com/davatorium/rofi)
 - Shell: [**`Fish`**](https://github.com/fish-shell/fish-shell)
 - Font: [**`JetBrainsMono`**](https://www.jetbrains.com/lp/mono/)
 - Icon: [**`Nordzy-icon`**](https://github.com/alvatip/Nordzy-icon)
 - GTK3:
 - Sound driver: [**`PipeWire`**](https://github.com/mikeroyal/PipeWire-Guide#Installing-PipeWire-on-Arch-Linux)

</br>

# :page_with_curl: Table of Contents 

### Basic installation
+ [Installing Arch Linux](#Install-Arch-Linux)
+ [Installing packages and programs](#Installing-packages-and-programs)
+ [Basic configuration](#basic-configurationt)

<h3 align="center"> Install Arch Linux </h3>

<a name="Install-Arch-Linux"></a>

[Back to the Top](#basic-installation)

<h3 align="center"> Installing packages and programs </h3>

<a name="Installing-packages-and-programs"></a>

Basic Installation Packages: `neofetch, nano, bspwm, sxhkd, kitty, rofi, picom, polybar, lemurs, xorg, xorg-xinit`
~~~
sudo pacman -S neofetch nano
~~~
~~~
sudo pacman -S bspwm sxhkd kitty rofi picom polybar lemurs
~~~

Xorg:
~~~
sudo pacman -S xorg xorg-xinit
~~~

Since the fonts are not installed, they need to be installed:
~~~
sudo pacman -S gnu-free-fonts
~~~

next the system must be restarted

[Back to the Top](#basic-installation)

<h3 align="center"> Basic configuration </h3>

<a name="basic-configurationt"></a>

The "~" symbol in the path of the file\directory means /home/{user} (home directory)

Some config files will be stored in ~/.config. If this directory is missing, then create it:
~~~
mkdir ~/.config
~~~

Next create the following directories:
~~~
mkdir ~/.config/bspwm sxhkd polybar
~~~

After creating the directories copy the local config files to the home directory:

Bspwm:
~~~
cp /usr/share/doc/bspwm/examples/bspwmrc ~/.config/bspwm
~~~

Sxhkd:
~~~
cp /usr/share/doc/bspwm/examples/sxhkdrc ~/.config/sxhkd
~~~

Polybar:
~~~
cp /usr/share/doc/polybar/examples/config.ini ~/.config/polybar/config
~~~

Now you need to make initial changes to the configuration files

Open file sxhkdrc:
~~~
nano ~/.config/sxhkd/sxhkdrc
~~~

This file stores the hotkey settings. We need to register our installed terminal. In my case it is: *Kitty*
~~~
super + Return    
  kitty
~~~

let's create a boot script for *polybar*

in the polybar directory, create a file with the name: launch.sh
~~~
nano ~/.config/polybar/launch.sh
~~~

In this file we write:
~~~

~~~

[Back to the Top](#basic-installation)
