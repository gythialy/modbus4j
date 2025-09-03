# modbus4j

A high-performance and ease-of-use implementation of the Modbus protocol written in Java by Infinite Automation Systems and Serotonin Software. Supports ASCII, RTU, TCP, and UDP transports as slave or master, automatic request partitioning and response data type parsing.

A public Maven Repository is now available with the latest builds add this to your pom.xml

```xml
<repositories>
    <repository>
        <id>central</id>
        <url>https://repo.maven.apache.org/maven2</url>
    </repository>
    <repository>
        <id>github</id>
        <url>https://maven.pkg.github.com/gythialy/modbus4j</url>
        <snapshots>
            <enabled>true</enabled>
        </snapshots>
    </repository>
</repositories>
```

The dependency information is:

```xml
<dependency>
  <groupId>com.infiniteautomation</groupId>
  <artifactId>modbus4j</artifactId>
  <version>3.1.1</version>
</dependency>
```
