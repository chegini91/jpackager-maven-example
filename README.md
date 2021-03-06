# jpackager-maven-example

Sample project for the jlink-jpackager-maven-plugin

## Prerequisites

- [JDK](http://jdk.java.net/)
- [Maven](https://maven.apache.org/)
- [jlink-jpackager-maven-plugin](https://github.com/agilhard-oss/jlink-jpackager-maven-plugin)

You need to use the special JDK-12 Early Access build that includes JPackager support to use this example.

This JPackager JDK-12 Early Access build can be downloaded from 
[https://jdk.java.net/jpackage/](https://jdk.java.net/jpackage/)

Alternatively you can also use the JDK-11 backported JPackager tool wich is mentioned in
[Filling the Packager gap - OpenJDK mailing list - Java.net](http://mail.openjdk.java.net/pipermail/openjfx-dev/2018-September/022500.html)

The [link-jpackager-maven-plugin](https://github.com/agilhard-oss/jlink-jpackager-maven-plugin) is not (yet?)
available on maven central you must download,
compile and install that to your maven Repository before you can use this example.

Native packages will be generated using tools on the target platform. 

For Linux and Mac make sure you have the packaging tools for the used packaging type installed.

For Windows, there are two additional tools that developers will need to install if they want to generate native packages:

- exe — Inno Setup, a third-party tool, is required to generate exe installers
- msi — Wix, a third-party tool, is required to generate msi installers

[Inno Setup](http://www.jrsoftware.org/isinfo.php)
[Inno Setup Download](http://www.jrsoftware.org/isdl.php)

[Wix Toolset](http://wixtoolset.org)
[Wix Toolset Downloads](http://wixtoolset.org/releases/)




