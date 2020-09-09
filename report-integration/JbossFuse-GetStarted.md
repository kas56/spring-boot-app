Jboss Fuse 7.7.0 - Karaf installer (https://developers.redhat.com/download-manager/file/fuse-karaf-7.7.0.fuse-770009-redhat-00002.zip)

Java 8

Git

##Jboss Fuse start

    \bin\karaf.bat debug
    
Debug port: 5005

##Установить features

    features:install cxf-ws-security

    features:install camel-dozer

###Hawtio
    feature:install hawtio

Для включения доступа пользователю admin расскомментировать в файле fuse-karaf-7.7.0.fuse\etc\users.properties 
2 последние строчки

http://localhost:8181/hawtio

