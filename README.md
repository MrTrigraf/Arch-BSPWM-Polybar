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
+ [Installing Arch Linux](https://github.com/MrTrigraf/arch-bspwm-polybar#Install-Arch-Linux)
+ [Installing packages and programs](https://github.com/MrTrigraf/arch-bspwm-polybar#Installing-packages-and-programs)
+ [Basic configuration](https://github.com/MrTrigraf/arch-bspwm-polybar#Basic-configuration)

<h3 align="center"> Install Arch Linux </h3>

[Back to the Top](#basic-installation)

<h3 align="center"> Installing packages and programs </h3>

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



[Back to the Top](#basic-installation)

