# cse-java-chassis-build
The docker image include a full build environment for cse-java-chassis.

## Build docker images
Clone the code here and enter the folder. Then perform the following command:
```
docker build -t cse-java-chassis-build .
```

## How to use
For example:
```
docker run --rm -it --name zqmvn -v /root/tmp/java-chassis-0.1.0:/usr/src/project -w /usr/src/project cse-java-chassis-build mvn clean install
```
