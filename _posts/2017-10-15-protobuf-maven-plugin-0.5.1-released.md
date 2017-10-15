---
layout: post
title: Maven Protocol Buffers Plugin 0.5.1 Released
---

We are happy to announce a new release of Maven Protocol Buffers Plugin,
which is now available in Maven Central.

You can include the plugin in your POM in the following way:

```xml
<project>
  ...
  <build>
    <!-- To define the plugin version in your parent POM -->
    <pluginManagement>
      <plugins>
        <plugin>
          <groupId>org.xolstice.maven.plugins</groupId>
          <artifactId>protobuf-maven-plugin</artifactId>
          <version>0.5.1</version>
        </plugin>
        ...
      </plugins>
    </pluginManagement>
    <!-- To use the plugin goals in your POM or parent POM -->
    <plugins>
      <plugin>
        <groupId>org.xolstice.maven.plugins</groupId>
        <artifactId>protobuf-maven-plugin</artifactId>
        <version>0.5.1</version>
      </plugin>
      ...
    </plugins>
  </build>
  ...
</project>
```

Full plugin documentation is available on the
[plugin web site](https://www.xolstice.org/protobuf-maven-plugin/).
