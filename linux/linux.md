# Command
### cp
```
# cp source destination

# copy a file to a different directory
cp myfile.txt /path/to/destination/

# copy a file and rename it
cp myfile.txt /path/to/destination/newfile.txt

```

### ( Single Parentheses )
Single parenthesis will run the commands inside in a subshell. This means that they run through all of the commands inside, and then return a single exit code.
[Ref](https://dev.to/rpalo/bash-brackets-quick-reference-4eh6)
```
(cd path/example && npm i)


# npm i in the target directory without changing actual directory
```

# Command line utility
## NatCat
Netcat is a command line utility that allows you to send and receive data over the network. It is mostly used by security specialists and hackers to analyze a network in traffic.
[Ref](https://www.section.io/engineering-education/introduction-to-netcat/)
### Install NatCat
```
sudo yum install -y nc
```

```
# nc -vz [target] [port]

nc -vz google.com 8080

#To check if the installation was successful, we can scan Google to see if we can reach it. In this case we have checked the version of Netcat and connection to Google on port 8080

```

