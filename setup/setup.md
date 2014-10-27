# Installing OpenFL

## Haxe

First, you will need to install Haxe and Neko. OpenFL uses Haxe to power the build process, and Neko to run the command-line tools. Both are included in the following installers, one for each platform:

 * [Windows](http://haxe.org/file/haxe-3.1.3-win.exe)
 * [Mac](http://haxe.org/file/haxe-3.1.3-osx-installer.pkg)
 * [Linux](http://www.openfl.org/builds/haxe/haxe-3.1.3-linux-installer.tar.gz)

_If you are a Linux user, we recommend that you do use the above install script instead of your own package manager. The versions of Haxe and Neko distributed on Linux package repositories tend to be old, or experience other issues after the install._

## OpenFL

With the latest versions of Haxe and Neko installed, open a command-prompt (Windows) or terminal (Mac/Linux) and run these commands:

    haxelib install openfl
    haxelib run openfl setup

To confirm that OpenFL is installed and working properly, try running the "openfl" command:

    openfl
