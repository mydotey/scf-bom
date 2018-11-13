# scf-bom: all library works together

Dependency bom for [SCF](https://github.com/mydotey/scf).

## Maven Dependency

```xml
    <dependencyManagement>
        <dependencies>
            <dependency>
                <groupId>org.mydotey.scf</groupId>
                <artifactId>scf-bom</artifactId>
                <version>1.5.1</version>
                <type>pom</type>
                <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>

    <dependencies>
        <dependency>
            <groupId>org.mydotey.scf</groupId>
            <artifactId>scf-core</artifactId>
        </dependency>
        <dependency>
            <groupId>org.mydotey.scf</groupId>
            <artifactId>scf-simple</artifactId>
        </dependency>
        <dependency>
            <groupId>org.mydotey.scf</groupId>
            <artifactId>scf-labeled</artifactId>
        </dependency>
        <dependency>
            <groupId>org.mydotey.scf</groupId>
            <artifactId>scf-yaml</artifactId>
        </dependency>
        <dependency>
            <groupId>org.mydotey.scf</groupId>
            <artifactId>scf-apollo</artifactId>
        </dependency>
    </dependencies>
```

## Developers

- Qiang Zhao <koqizhao@outlook.com>
