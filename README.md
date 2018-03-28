# ubuntu-dev-env-setup


## Tools I want:
* vim: `sudo apt install vim`
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

## Open JDK
* `sudo apt-get install openjdk-8-jdk`
* `sudo vi /etc/profile.d/jdk_env.sh`
```shell
export JAVA_HOME=/usr/lib/jvm/java-1.8.0-openjdk-amd64
export PATH=$PATH:$JAVA_HOME/bin
```
## Oralce JDK
* sudo add-apt-repository ppa:webupd8team/java
* sudo apt-get update
* sudo apt-get install oracle-java8-installer
* java -version
* vi /etc/profid.d/jdk-env.sh
```shell
export JAVA_HOME=/usr/lib/jvm/java-8-oracle
export PATH="$JAVA_HOME/bin:$PATH"
```
* Referenes:
  * https://medium.com/coderscorner/installing-oracle-java-8-in-ubuntu-16-10-845507b13343
  * https://launchpad.net/~webupd8team/+archive/ubuntu/java
