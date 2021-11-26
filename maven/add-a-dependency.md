# 의존성 추가

`pom.xml` 파일에 의존성을 추가할 때는 `<dependencies>` 태그 안에 `<dependency>`태그를 포함하여 관리한다.

예시: jdbc 드라이버와 jstl 라이브러리에 대한 의존성을 추가하는 경우
```xml
<dependencies>
    <dependency>
        <groupId>mysql</groupId>
        <artifactId>mysql-connector-java</artifactId>
        <version>8.0.21</version>
    </dependency>
    <dependency>
        <groupId>jstl</groupId>
        <artifactId>jstl</artifactId>
        <version>1.2</version>
    </dependency>
</dependencies>
```