# HOW TO USE

  ADD something like in the pom file

```
        <repository>
            <id>github</id>
            <url>https://raw.githubusercontent.com/difisoft/maven-repos/main</url>
            <snapshots>
                <enabled>true</enabled>
                <updatePolicy>always</updatePolicy>
            </snapshots>
            <releases>
                <enabled>true</enabled>
                <updatePolicy>always</updatePolicy>
            </releases>
        </repository>
```
