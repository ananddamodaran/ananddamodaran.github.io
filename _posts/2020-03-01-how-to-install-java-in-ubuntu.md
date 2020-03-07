---
layout: post
title: Install Oracle Java JDK 13.0.2 in Ubuntu 18.04 LTS
excerpt: "Getting started with Java."
categories: [Java]
comments: false
image:
  feature:
  credit: 
  creditlink: 
---
Oracle Java SE 13 was released September 2019. The latest update of Java JDK is 13.0.2. In this post we install the JDK in Ubuntu Linux 18.04 LTS.

![image](https://miro.medium.com/max/8512/0*-hMqapazeDO-IOck)

{% highlight shell %}
# Remove the OpenJDK/JRE completely 
$ sudo apt-get purge openjdk-\* 

$ sudo mkdir -p /usr/local/java 

# Download the Oracle Java JDK for Linux.
$ wget --no-check-certificate -c --header  "Cookie: oraclelicense=accept-securebackup-cookie" "https://download.oracle.com/otn-pub/java/jdk/13.0.2+8/d4173c853231432d94f001e99d882ca7/jdk-13.0.2_linux-x64_bin.tar.gz"

$ sudo cp -r jdk-13.0.2_linux-x64_bin.tar.gz /usr/local/java/

$ cd /usr/local/java

# Unpack the compressed Java binaries
$ sudo tar xvzf jdk-13.0.2_linux-x64_bin.tar.gz

# Edit the system PATH file /etc/profile and add the following system variables to your system path.
$ sudo vim /etc/profile

JAVA_HOME=/usr/local/java/jdk-13.0.2
JRE_HOME=$JAVA_HOME/jre
PATH=$PATH:$JAVA_HOME/bin:$JRE_HOME/bin
export JAVA_HOME
export JRE_HOME
export PATH

# Inform Ubuntu Linux system where your Oracle Java JDK/JRE is located.
$ sudo update-alternatives --install "/usr/bin/java" "java" "/usr/local/java/jdk-13.0.2/bin/java" 1

$ sudo update-alternatives --install "/usr/bin/javac" "javac" "/usr/local/java/jdk-13.0.2/bin/javac" 1

# Inform Ubuntu Linux system that Oracle Java JDK/JRE must be the default Java.
$ sudo update-alternatives --set java /usr/local/java/jdk-13.0.2/jre/bin/java

$ sudo update-alternatives --set javac /usr/local/java/jdk-13.0.2/bin/javac

#Reload the system PATH  
$ . /etc/profile

# Test to see if Oracle Java is installed correctly
$ java -version

{% endhighlight %}

:smiley:
