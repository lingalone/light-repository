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

```