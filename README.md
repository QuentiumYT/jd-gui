# JD-GUI

JD-GUI is a standalone graphical utility that displays Java sources from class files.

> This is a fork of the original JD-Core project, which is no longer maintained. I tried to fix and update dependencies to make it live longer and be useful for the community. If you have a good knowledge of Java and want to help, feel free to contribute. 😃

![Preview of JD-GUI](https://raw.githubusercontent.com/QuentiumYT/jd-gui/master/src/website/img/jd-gui.png)

- Java Decompiler project home page: https://java-decompiler.github.io
- JD-GUI source code: https://github.com/QuentiumYT/jd-gui
- JD-GUI public releases: https://launchpad.net/~quentiumyt/+archive/ubuntu/jd-gui

## Description
JD-GUI is a standalone graphical utility that displays Java source codes of ".class" files. You can browse the reconstructed source code with the JD-GUI for instant access to methods and fields.

## How to build JD-GUI ?
```
> git clone https://github.com/QuentiumYT/jd-gui.git
> cd jd-gui/
> ./gradlew build 
```

generate :
- _"build/libs/jd-gui-x.y.z.jar"_
- _"build/libs/jd-gui-x.y.z-min.jar"_
- _"build/distributions/jd-gui-windows-x.y.z.tar"_
- _"build/distributions/jd-gui-windows-x.y.z.zip"_
- _"build/distributions/jd-gui-osx-x.y.z.tar"_
- _"build/distributions/jd-gui-osx-x.y.z.zip"_
- _"build/distributions/jd-gui-x.y.z-1\_all.deb"_
- _"build/distributions/jd-gui-x.y.z-1.noarch.rpm"_

## How to launch JD-GUI ?
- Double-click on _"jd-gui-x.y.z.jar"_
- Double-click on _"jd-gui.exe"_ application from Windows
- Double-click on _"JD-GUI"_ application from Mac OSX
- Execute _"java -jar jd-gui-x.y.z.jar"_ or _"java -classpath jd-gui-x.y.z.jar org.jd.gui.App"_

## How to use JD-GUI ?
- Open a file with menu "File > Open File..."
- Open recent files with menu "File > Recent Files"
- Drag and drop files from your file explorer

## How to extend JD-GUI ?
```
> ./gradlew idea 
```
generate Idea Intellij project
```
> ./gradlew eclipse
```
generate Eclipse project
```
> java -classpath jd-gui-x.y.z.jar;myextension1.jar;myextension2.jar org.jd.gui.App
```
launch JD-GUI with your extensions

## How to uninstall JD-GUI ?
- Java: Delete "jd-gui-x.y.z.jar" and "jd-gui.cfg".
- Mac OSX: Drag and drop "JD-GUI" application into the trash.
- Windows: Delete "jd-gui.exe" and "jd-gui.cfg".

## License
Released under the [GNU GPLv3](LICENSE).

## Donations
Did JD-GUI help you to solve a critical situation? Do you use JD-Eclipse daily? What about making a donation?

[![paypal](https://raw.githubusercontent.com/QuentiumYT/jd-gui/master/src/website/img/btn_donate_euro.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=C88ZMVZ78RF22) [![paypal](https://raw.githubusercontent.com/QuentiumYT/jd-gui/master/src/website/img/btn_donate_usd.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CRMXT4Y4QLQGU)
