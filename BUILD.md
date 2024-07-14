# OpenStar Reqirements
If on **macOS**, you will need to be on macOS Montery or macOS Ventrua. 
If on **Windows**, you will need to be on Windows 8. Runing from Windows 10 will display "This App cannot be opened"
There are some videos of how to fix it!
If on **Linux**, you will need to be on the Latest Verion of **Linux**.


## Building on Windows
Before you build, Intstall Visual Studio on [Visual Studio's Download Page](https://visualstudio.microsoft.com/downloads/). 

DO NOT Go to the workflows. Go to the individual components and install the following components: 

- MSVC v142 - VS 2019 C++ x64/x86 build tools
- Windows SDK (10.0.17763.0)



After thats done, [Install Haxe](https://haxe.org/download/), then go to **[Seting up HaxeFlixel and OpenFl](#seting-up-haxeflixel--openfl)**![Unknown-1](https://github.com/user-attachments/assets/ef63ef97-bb80-425b-99c7-4878c0770f4f)


## Building on macOS
 The build and compile of OpenStar on macOS is you need to download and install Xcode show me the App Store. if you don't want to install on the App Store, go to [The Apple Developer website](https://developer.apple.com/xcode/). 
> Here is a quick note. Depending on your Wi-Fi, This might download faster or slow. Some Xcode app files are big. Just go grab some popcorn or any type of snack until it's installed.

If Xcode is already installed, or it is downloaded, [Install Haxe](https://haxe.org/download/), then go to **[Seting up HaxeFlixel & OpenFl](#set-up-haxeflixel--openfl)**

## Building on Linux
**Run the following commands before building:**
If Debian: ``sudo apt install build-essential``

If Arch: ``sudo pacman -Syu gcc``

If centOS: ``sudo yum install gcc-c++``

If Fedora: ``sudo dnf groupinstall 'Development Tools'``


If CGG is already installed on your Linux, [Install Haxe](https://haxe.org/download/), then go to **[Seting up HaxeFlixel and OpenFl](#seting-up-haxeflixel--openfl)**


# Seting up HaxeFlixel & OpenFl

After you installed Haxe, we're on the following commands in your terminal:

```
haxelib install lime
haxelib install openfl
haxelib install flixel
```
Run the following command to set up lime:
``haxelib run lime setup flixel``

If lime is already set up or it is set up, install ``flixel`
```
haxelib install flixel-tools
haxelib run flixel-tools setup
```
# Going to the directory
Run the following command to go to the directory:
``cd C:/Users/youruser/where/OpenStar-master``
# Building
To build OpenStar, you need to run the following commands: 
If you are running macOS: ``lime build mac``
If you are running Windows: ``lime build windows``
If you are running Linux: ``lime build linux``










