# hello-world.

HIHI
tutorial repoditory


<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 https://maven.apache.org/xsd/maven-4.0.0.xsd">
  <modelVersion>4.0.0</modelVersion>
  <groupId>javaPrj</groupId>
  <artifactId>javaPrj</artifactId>
  <version>0.0.1-SNAPSHOT</version>
  <repositories>
  <repository>
      <id>jitpack.io</id>
      <url>https://jitpack.io</url>
  </repository>
</repositories>
  <dependencies>
  <dependency>
    <groupId>com.github.shin285</groupId>
    <artifactId>KOMORAN</artifactId>
    <version>3.3.4</version>
  </dependency>
</dependencies>
  <build>
    <sourceDirectory>src</sourceDirectory>
    <plugins>
      <plugin>
        <artifactId>maven-compiler-plugin</artifactId>
        <version>3.8.0</version>
        <configuration>
          <source>1.8</source>
          <target>1.8</target>
        </configuration>
      </plugin>
    </plugins>
  </build>
</project>
