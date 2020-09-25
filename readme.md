```
<repositories>
    <repository>
        <id>gitee-lingalone-maven</id>
        <url>https://gitee.com/lingalone/light-repository/raw/master/</url>
    </repository>
    <repository>
        <id>github-lingalone-maven</id>
        <url>https://github.com/lingalone/light-repository/raw/master</url>
    </repository>
</repositories>
```

mvn deploy 命令
```$shell

mvn deploy:deploy-file -Dmaven.test.skip=true -Dfile=E:\greenplum.jar -DgroupId=com.pivotal -DartifactId=greenplum -Dversion=1.0.0 -Dpackaging=jar -DrepositoryId=localRepository -Durl=file:D:/lib/lig
ht-repository


mvn install:install-file -Dfile=/Users/lingalone/Downloads/sdk-java-27966921/taobao-sdk-java-1.1.0.jar -DgroupId=com.taobao -DartifactId=taobao-sdk-java -Dversion=1.1.0 -Dpackaging=jar

mvn deploy:deploy-file -DgroupId=com.taobao -DartifactId=taobao-sdk-java -Dversion=1.1.0 -Dpackaging=jar -Dfile=/Users/lingalone/Downloads/sdk-java-27966921/taobao-sdk-java-1.1.0.jar -Durl=file:/Users/lingalone/code/repository -DrepositoryId=localRepository



```
淘宝客sdk
```
mvn install:install-file -Dfile=/Users/lingalone/Downloads/sdk-java-27966921/taobao-sdk-java-1.1.1.jar -DgroupId=com.taobao -DartifactId=taobao-sdk-java -Dversion=1.1.1 -Dpackaging=jar

mvn deploy:deploy-file -DgroupId=com.taobao -DartifactId=taobao-sdk-java -Dversion=1.1.1 -Dpackaging=jar -Dfile=/Users/lingalone/Downloads/sdk-java-27966921/taobao-sdk-java-1.1.1.jar -Durl=file:/Users/lingalone/code/repository -DrepositoryId=localRepository


```

京东sdk

```
mvn install:install-file -Dfile=/Users/lingalone/Downloads/open-api-sdk-2.0.jar -DgroupId=com.jd -DartifactId=open-api-sdk -Dversion=2.0 -Dpackaging=jar

mvn deploy:deploy-file -DgroupId=com.jd -DartifactId=open-api-sdk -Dversion=2.0 -Dpackaging=jar -Dfile=/Users/lingalone/Downloads/open-api-sdk-2.0.jar -Durl=file:/Users/lingalone/code/repository -DrepositoryId=localRepository


```


小米推送sdk

```
mvn install:install-file -Dfile=/Users/lingalone/Downloads/MiPush_SDK_Server_Http2_1.0.9.jar -DgroupId=com.xiaomi.push -DartifactId=mi-push-sdk -Dversion=1.0.9 -Dpackaging=jar

mvn deploy:deploy-file -DgroupId=com.xiaomi.push -DartifactId=mi-push-sdk -Dversion=1.0.9 -Dpackaging=jar -Dfile=/Users/lingalone/Downloads/MiPush_SDK_Server_Http2_1.0.9.jar -Durl=file:/Users/lingalone/code/repository -DrepositoryId=localRepository


```

oppo推送sdk

```
mvn install:install-file -Dfile=/Users/lingalone/Downloads/opush-server-sdk-1.0.5.jar -DgroupId=com.oppo.push -DartifactId=opush-server-sdk -Dversion=1.0.5 -Dpackaging=jar

mvn deploy:deploy-file -DgroupId=com.oppo.push -DartifactId=opush-server-sdk -Dversion=1.0.5 -Dpackaging=jar -Dfile=/Users/lingalone/Downloads/opush-server-sdk-1.0.5.jar -Durl=file:/Users/lingalone/code/repository -DrepositoryId=localRepository


```

vivo推送sdk

```
mvn install:install-file -Dfile=/Users/lingalone/Downloads/vpush-server-sdk-2.2.jar -DgroupId=com.vivo.push -DartifactId=vpush-server-sdk -Dversion=2.2 -Dpackaging=jar

mvn deploy:deploy-file -DgroupId=com.vivo.push -DartifactId=vpush-server-sdk -Dversion=2.2 -Dpackaging=jar -Dfile=/Users/lingalone/Downloads/vpush-server-sdk-2.2.jar -Durl=file:/Users/lingalone/code/repository -DrepositoryId=localRepository


```