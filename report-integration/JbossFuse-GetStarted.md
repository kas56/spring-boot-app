#Подготовка среды
##Скачать/установить
1. Jboss Fuse 7.7.0 - Karaf installer (https://developers.redhat.com/download-manager/file/fuse-karaf-7.7.0.fuse-770009-redhat-00002.zip)
2. Java 8
3. Git
4. Eclipse
4.1 Установить tools в Eclipse
    
    Help > Install New Software… > Work with: Jboss - http://download.jboss.org/jbosstools/photon/stable/updates/
    
    Выбрать группу:Red Hat Fuse Tooling	


https://tools.jboss.org/features/fusetools.html

##Jboss Fuse start

    \bin\fuse.bat debug
    
Debug port: 5005

##Установить features
В консоли ввести

    features:install cxf-ws-security

    features:install camel-dozer

    feature:install hawtio

##Настройка Jboss Fuse

Для включения доступа пользователю admin расскомментировать в файле fuse-karaf-7.7.0.fuse\etc\users.properties 
2 последние строчки

http://localhost:8181/hawtio

    Lodin: admin
    Password: admin
    
