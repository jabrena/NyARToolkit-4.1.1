# NyARToolkit-4.1.1

Migration to Maven from source:
https://osdn.jp/projects/nyartoolkit/downloads/57614/NyARToolkit-4.1.1.zip/

``` bash
mvn archetype:generate -DgroupId=jp.nyatla.nyartoolkit -DartifactId=nyartoolkit -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
```

Getting Started with Maven:

``` xml
    <repository>
        <id>jitpack.io</id>
        <url>https://jitpack.io</url>
    </repository>

    <dependency>
        <groupId>com.github.jabrena</groupId>
        <artifactId>NyARToolkit-4.1.1</artifactId>
        <version>v4.1.1</version>
    </dependency>
```

Further information:
https://jitpack.io/#jabrena/NyARToolkit-4.1.1/v4.1.1

