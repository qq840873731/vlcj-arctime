vlcj-arctime
====

vlcj-arctime is a fork of vlcj aimed at getting ArcTime to work on modern Linux distributions. 



## Building

The project is at the moment built with OpenJDK 8 on Linux. This will
work just fine when using Maven to build the project from the command-line.

For building on a fresh Ubuntu 20.04, these steps should be run:

```bash
sudo apt install git maven openjdk-8-jdk

git clone https://github.com/wegank/vlcj-arctime.git
cd vlcj-arctime
mvn package

# Replace /path/to/arctime with your own path to ArcTime
cp target/vlcj-4.2.0.jar /path/to/arctime/ArcTime_lib/
```



License
-------

vlcj-arctime is provided under the GPL, version 3 or later.

