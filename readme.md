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

```
mvn install:install-file -Dfile=/Users/lingalone/Downloads/sdk-java-27966921/taobao-sdk-java-1.1.1.jar -DgroupId=com.taobao -DartifactId=taobao-sdk-java -Dversion=1.1.1 -Dpackaging=jar

mvn deploy:deploy-file -DgroupId=com.taobao -DartifactId=taobao-sdk-java -Dversion=1.1.1 -Dpackaging=jar -Dfile=/Users/lingalone/Downloads/sdk-java-27966921/taobao-sdk-java-1.1.1.jar -Durl=file:/Users/lingalone/code/repository -DrepositoryId=localRepository


```