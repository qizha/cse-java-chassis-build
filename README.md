# cse-java-chassis-build
The docker image include a full build environment for cse-java-chassis.

## How to use
For example:
```
docker run --rm -it --name zqmvn -v /root/tmp/java-chassis-0.1.0:/usr/src/project -w /usr/src/project cse-java-chassis-build mvn clean install
```
