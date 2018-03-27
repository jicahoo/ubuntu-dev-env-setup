# ubuntu-dev-env-setup

## JDK
* `sudo apt-get install openjdk-8-jdk`
* `sudo vi /etc/profile.d/jdk_env.sh`
```shell
export JAVA_HOME=/usr/lib/jvm/java-1.8.0-openjdk-amd64
export PATH=$PATH:$JAVA_HOME/bin
```
