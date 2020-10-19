# WebGoat workshop

For more information about WebGoat visit https://owasp.org/www-project-webgoat/

## Prerequisite

- Download [ZAP](https://www.zaproxy.org/download/) and install it on your machine. If you have another proxy you can use that one as well of course.

If you are **not** able to use Docker also download: (you do not need to install anything on your machine!)

- Download [WebGoat v8.1.0](https://github.com/WebGoat/WebGoat/releases/tag/v8.1.0) 
- Download [WebWolf v8.1.0](https://github.com/WebGoat/WebGoat/releases/tag/v8.1.0)
- Download [Java 14](https://jdk.java.net/archive/) only download, see below.
- Download [ZAP](https://www.zaproxy.org/download/) and install it on your machine. If you have another proxy you can use that one as well of course.
- Docker (optional)

You should be able to change the proxy settings of your laptop, if not please download Firefox Portable Edition (https://portableapps.com/apps/internet/firefox_portable)

## Running WebGoat

Depending on your choice above (Docker or no Docker) either choose 'Run with Docker' or 'Run with jar file'

### Run with Docker

```
docker pull webgoat/goatandwolf:v8.1.0
```

### Run with jar file

Copy all the downloaded files to one folder, for example `/Users/me/workshop` 
Unzip the downloaded Java 14 zip file and open a terminal and go to the folder you created above:

```
java -jar webgoat-8.1.0.jar
```

On a Mac this would be: `jdk-14.0.1.jdk/Contents/Home/bin/java -jar webgoat-server-8.1.0.jar` 



