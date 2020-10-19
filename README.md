# WebGoat workshop

For more information about WebGoat visit https://owasp.org/www-project-webgoat/

## Prerequisite

For WebGoat you only need to download binaries, you do not need to install anything on your machine!

- Download [WebGoat v8.1.0](https://github.com/WebGoat/WebGoat/releases/tag/v8.1.0) 
- Download [WebWolf v8.1.0](https://github.com/WebGoat/WebGoat/releases/tag/v8.1.0)
- Download [Java 14](https://jdk.java.net/archive/) only download, see below.
- Download [ZAP](https://www.zaproxy.org/download/) and install it on your machine. If you have another proxy you can use that one as well of course.
- Docker (optional)

You should be able to change the proxy settings of your laptop, if not please download Firefox Portable Edition (https://portableapps.com/apps/internet/firefox_portable)

## Running WebGoat

Copy all the downloaded files to one folder, for example `/Users/me/workshop` 

### Running jar file

Unzip the downloaded Java 14 zip file and open a terminal and go to the folder you created above:

```
java -jar webgoat-8.1.0.jar
```

On a Mac this would be: `jdk-14.0.1.jdk/Contents/Home/bin/java -jar webgoat-server-8.1.0.jar` 


### Using Docker image from Docker Hub

**Prerequisite: Docker should be present on laptop**


```
docker pull webgoat/goatandwolf:v8.1.0
```
