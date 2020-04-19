# i
1. Install make
	- sudo apt-get update -y
- sudo apt-get install -y make

2. install cmake
	- sudo apt-get update -y
- sudo apt-get install -y cmake-gui

3. install openjdk8
	- sudo apt-get update && sudo apt-get upgrade
- sudo apt-get install openjdk-8-jdk
- java -version
- javac -version
- sudo apt-get install openjdk-8-jre
- echo "JAVA_HOME=$(which java)" | sudo tee -a /etc/environment
- source /etc/environment
- echo $JAVA_HOME
- sudo apt update
- sudo apt install openjdk-8-jdk
4. NetBeans 8.2 Released, How to Install it in Ubuntu 16.04
	https://websiteforstudents.com/how-to-install-netbeans-on-ubuntu-16-04-17-10-18-04/
- cd /tmp && wget -c http://download.netbeans.org/netbeans/8.2/final/bundles/netbeans-8.2-linux.sh
- chmod +x netbeans-8.2-linux.sh 
- sudo ./netbeans-8.2-linux.sh
5. install codeblock
	- sudo apt install codeblocks
- wget http://sourceforge.net/projects/codeblocks/files/Binaries/17.12/Linux/Debian%20stable/codeblocks_17.12-1_amd64_stable.tar.xz
- sudo tar xvf codeblocks_17.12-1_amd64_stable.tar.xz
- sudo apt install ./codeblocks_17.12-1_amd64.deb ./codeblocks-common_17.12-1_all.deb ./libcodeblocks0_17.12-1_amd64.deb ./codeblocks-dev_17.12-1_amd64.deb ./codeblocks-headers_17.12-1_all.deb ./*wx*.deb
- sudo apt install gcc
- sudo apt install clang
- sudo apt install mingw-w64
6. install pycharm
	https://itsfoss.com/install-pycharm-ubuntu/
- sudo add-apt-repository ppa:ubuntu-desktop/ubuntu-make
- sudo apt-get update
- sudo apt-get install ubuntu-make
- umake ide pycharm
- umake ide pycharm-professional
7. install android studio
	https://websiteforstudents.com/how-to-install-android-studio-ide-for-linux-on-ubuntu-16-04-18-04-18-10/
- wget https://dl.google.com/dl/android/studio/ide-zips/3.2.1.0/android-studio-ide-181.5056338-linux.zip -P /tmp
- sudo unzip -d /opt /tmp/android-studio-ide-181.5056338-linux.zip
- sh /opt/android-studio/bin/studio.sh
8. install python 3.7
	https://websiteforstudents.com/installing-the-latest-python-3-7-on-ubuntu-16-04-18-04/
https://tecadmin.net/install-python-3-7-on-ubuntu-linuxmint/
- sudo apt update
- sudo apt install build-essential zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev libssl-dev libreadline-dev libffi-dev wget
- cd /tmp
- wget https://www.python.org/ftp/python/3.7.2/Python-3.7.2.tar.xz
tar -xf Python-3.7.2.tar.xz
- cd Python-3.7.2
- ./configure --enable-optimizations
- make -j 1
- sudo make altinstall
9. install nodejs
	https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-16-04
- sudo apt-get install nodejs
- sudo apt-get install npm
- nodejs -v
10. install Arduino
	https://websiteforstudents.com/how-to-install-arduino-ide-on-ubuntu-18-04-16-04/
- cd /tmp
- wget https://downloads.arduino.cc/arduino-1.8.12-linux64.tar.xz
- tar -xvf arduino-1.8.12-linux64.tar.xz
- cd arduino-1.8.12/
- sudo ./install.sh
11. install wxbuilder
	https://zoomadmin.com/HowToInstall/UbuntuPackage/wxformbuilder
- sudo apt-get update -y
- sudo apt-get install -y wxformbuilder

12. Install git form source	https://www.digitalocean.com/community/tutorials/how-to-install-git-on-ubuntu-16-04
-sudo apt-get install git
13. opencv3.4 or 4.2	
14. darknet	
	
	
	






