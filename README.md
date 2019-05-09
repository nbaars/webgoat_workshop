# WebGoat workshop

## https://github.com/nbaars/webgoat_workshop/
## Prerequisite

- Download [ZAP](https://github.com/zaproxy/zaproxy/wiki/Downloads) and install it on your machine.
- Download [WebGoat v8.0.0.M25](https://github.com/WebGoat/WebGoat/releases/tag/v8.0.0.M25)
- Download [Java 11](https://jdk.java.net/11/) only download, see below.
- Docker (optional)

You should be able to change the proxy settings of your laptop, if not please download Firefox Portable Edition (https://portableapps.com/apps/internet/firefox_portable)

## Running WebGoat

### Running jar file

**Prerequisite: Java 11 should be present on laptop**

Start WebGoat:

```
java -jar webgoat-8.0.0-M25.jar
```

### Using Docker image from Docker Hub

**Prerequisite: Docker should be present on laptop**

Copy [this](https://github.com/WebGoat/WebGoat/blob/develop/docker-compose.yml) `docker-compose` file to your local machine 

```
docker-compose up
```
