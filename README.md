# WebGoat workshop

For more information about WebGoat visit https://owasp.org/www-project-webgoat/

## Prerequisite

Before starting we need to have some tools available locally.

- Download [ZAP](https://www.zaproxy.org/download/) and install it on your machine. If you have another proxy you can use that one as well of course.

If you are **NOT** able to use Docker also download, you don't need to install anything on your system!

- Download [WebGoat v8.1.0](https://github.com/WebGoat/WebGoat/releases/tag/v8.1.0) 
- Download [WebWolf v8.1.0](https://github.com/WebGoat/WebGoat/releases/tag/v8.1.0)
- Download [Java 14](https://jdk.java.net/archive/) only download, see below.

You should be able to change the proxy settings of your laptop, if not please download Firefox Portable Edition (https://portableapps.com/apps/internet/firefox_portable)

## Running WebGoat

Depending on your choice above (Docker or no Docker) either choose 'Run with Docker' or 'Run with jar file'

### Run with Docker

```
docker pull webgoat/goatandwolf:v8.1.0
docker run -p 8080:8080 -p 9090:9090 -e TZ=Europe/Amsterdam webgoat/goatandwolf:v8.1.0
```

Open your favourite browser and browse to: http://localhost:8080/WebGoat

### Run with jar file

Copy all the downloaded files (WebGoat/WebWolf and Java 14) to one folder, unzip the downloaded Java 14 zip file and open a terminal and go to the folder you created, this folder should look like (depending on your platform)

```
jdk-14.0.1.jdk
jdk-14.01
webgoat-server-8.1.0.jar
webwolf-8.1.0.jar
```

Now execute the following command:

```
[Windows and Linux] jdk-14.0.1/bin/java -jar webgoat-8.1.0.jar
[Mac] jdk-14.0.1.jdk/Contents/Home/bin/java -jar webgoat-server-8.1.0.jar
```

Open your favourite browser and browse to: http://localhost:8080/WebGoat



