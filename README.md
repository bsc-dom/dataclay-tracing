# extrae-java
Maven repository for Extrae java dependencies
To include extrae and its aspects as a dependency in a maven project, add the following repository and dependencies to the `pom.xml`:

```xml
<repository>
    <id>Maven repository for Extrae java dependencies</id>
    <url>https://raw.github.com/bsc-ssrg/extrae-java/repository</url>
</repository>
```

```xml
<dependency>
    <groupId>es.bsc.dataclay</groupId>
    <artifactId>extrae</artifactId>
    <version>3.6.1</version>
</dependency>
<dependency>
    <groupId>es.bsc.dataclay</groupId>
    <artifactId>extrae-aspects</artifactId>
    <version>2.0.8-RC1</version>
</dependency>
```
