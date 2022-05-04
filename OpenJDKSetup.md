## Adding openJDK XX on MacOS

Downloading <openJDK_XX>.tar.gz version from https://openjdk.java.net/projects/jdk/

```
sudo mv <openJDK>.tar.gz /Library/Java/JavaVirtualMachines/
cd /Library/Java/JavaVirtualMachines/
sudo tar -xzf <openJDK>_bin.tar.gz
```
Add to .bash_profile

```
export JAVA_XX_HOME=$(/usr/libexec/java_home -vXX)
alias javaXX='export JAVA_HOME=$JAVA_XX_HOME'

# default to Java XX
javaXX
```



