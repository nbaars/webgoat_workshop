# WebGoat workshop

## https://github.com/nbaars/webgoat_workshop/
## Prerequisite

- Download [WebGoat v8.0.0.M26](https://github.com/WebGoat/WebGoat/releases/tag/v8.0.0.M26)
- Download [WebWolf v8.0.0.M26](https://github.com/WebGoat/WebGoat/releases/tag/v8.0.0.M26)
- Download [Java 11](https://jdk.java.net/archive/) only download, see below.
- Download [ZAP](https://www.zaproxy.org/download/) and install it on your machine. If you have another proxy you can use that one as well of course.
- Docker (optional)

You should be able to change the proxy settings of your laptop, if not please download Firefox Portable Edition (https://portableapps.com/apps/internet/firefox_portable)

## Running WebGoat

### Running jar file

**Prerequisite: Java 11 should be present on laptop**

Start WebGoat:

```
java -jar webgoat-8.0.0-M26.jar
```

### Using Docker image from Docker Hub

**Prerequisite: Docker should be present on laptop**

Copy [this](https://github.com/WebGoat/WebGoat/blob/develop/docker-compose.yml) `docker-compose` file to your local machine 

```
docker-compose up
```
