# Parasol
Parasol is a cross-platform TUI File designed to be minimal. Unlike most TUI file explorers, Parasol does not use the arrow keys for navigation, instead each file and directory is assigned a number and you can interact with the files and paths through their numbers.

This project was also a headstart to learn Java and Go, so while it's now developed in Java, the legacy Go code is kept in the "old" folder.

More features will come in future versions

## Download

You can download the latest release of Parasol [here](https://github.com/spacebanana420/parasol/releases)

### Requirements
* Java (recommended version 8 or above)
  * You can get Java by downloading JRE, JDK or OpenJDK. I recommend OpenJDK since it's free and open source.

### Officially tested systems:
* Linux (distro-agnostic)
* Windows

### Systems that probably work:
* BSD systems (FreeBSD, OpenBSD, etc)
* MacOS
* Systems that use the xdg desktop standard


## List of current commands

* help - displays the help menu
* size (number) - gets the size of the file of entry (number)


## How to build
* Install JDK or OpenJDK (recommended version 17 or above, older versions should work but are untested)
* Open a terminal in the root of the project
* Type the commands (not tested on cmd or powershell):
```
javac main.java
jar cfve parasol.jar main *.class */*.class
```
* Alternatively, you can run the build script with ```bash build.sh```

Parasol is now compiled and packaged into parasol.jar

Remember to delete the .class files


If you are curious about the code written in Go, that's the old version of Parasol before I rewrote it in Java. The code is located in the directory "old", as well as its respective build script.
