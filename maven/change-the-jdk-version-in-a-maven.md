# Change the JDK Version in a Maven

## [Change the JDK version in a Maven project](https://www.jetbrains.com/help/idea/maven-support.html#change_jdk)   
<br>

## pom.xml
```xml
    <properties>
        <maven.compiler.source>8</maven.compiler.source>    <!--here-->
        <maven.compiler.target>8</maven.compiler.target>    <!--here-->
    </properties>
```
or
```xml
    <plugin>
        <artifactId>maven-compiler-plugin</artifactId>
        <version>3.8.1</version>
        <configuration>
        <release>8</release>  <!--here-->
        </configuration>
    </plugin>
```