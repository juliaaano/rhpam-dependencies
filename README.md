# RHPAM Dependencies
[![Build Status](https://travis-ci.com/juliaaano/rhpam-dependencies.svg)](https://travis-ci.com/juliaaano/rhpam-dependencies)

Red Hat Process Automation Manager POM dependencies.

## Use as a parent in pom.xml
```xml
<parent>
    <groupId>com.juliaaano</groupId>
    <artifactId>rhpam-dependencies</artifactId>
    <version>1.1.0</version>
</parent>
```

## Use as an import in pom.xml
```xml
<dependencyManagement>
    <dependencies>
        <dependency>
            <groupId>com.juliaaano</groupId>
            <artifactId>rhpam-dependencies</artifactId>
            <version>1.1.0</version>
            <type>pom</type>
            <scope>import</scope>
        </dependency>
    </dependencies>
</dependencyManagement>
```
