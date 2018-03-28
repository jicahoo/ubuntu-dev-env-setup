# ubuntu-dev-env-setup


## Tools I want:
* JDK
* Git
* IntelliJ IDEA
* PyCharm
* Chrome (Download deb from google and `sudo apt install /path/to/xx.deb`)
* vscode (Download deb and install)
* maven. `sudo apt install maven`
* docker. docke-ce: https://docs.docker.com/install/linux/docker-ce/ubuntu/ Download deb and install.

## Upgrade ubuntu
* sudo apt update
* sudo apt upgrade

## JDK
* `sudo apt-get install openjdk-8-jdk`
* `sudo vi /etc/profile.d/jdk_env.sh`
```shell
export JAVA_HOME=/usr/lib/jvm/java-1.8.0-openjdk-amd64
export PATH=$PATH:$JAVA_HOME/bin
```
