---
layout: post
title: Maven Protocol Buffers Plugin 0.6.1 Released
---

We are happy to announce a new release of Maven Protocol Buffers Plugin,
which is now available in Maven Central.

Key new features:

* An option to use an argument file to avoid "Command line is too long" error.
  Requires protobuf compiler version 3.5.0 or higher.
* Additional goals to support generation of C# and JavaScript sources.

Full change log is available [here][2].  

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
          <version>0.6.1</version>
        </plugin>
        ...
      </plugins>
    </pluginManagement>
    <!-- To use the plugin goals in your POM or parent POM -->
    <plugins>
      <plugin>
        <groupId>org.xolstice.maven.plugins</groupId>
        <artifactId>protobuf-maven-plugin</artifactId>
        <version>0.6.1</version>
      </plugin>
      ...
    </plugins>
  </build>
  ...
</project>
```

Full plugin documentation is available on the [plugin web site][1].

[1]: https://www.xolstice.org/protobuf-maven-plugin/
[2]: https://www.xolstice.org/protobuf-maven-plugin/changes-report.html

