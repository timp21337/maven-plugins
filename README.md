# GitHub Maven Mojos
[Maven](http://maven.apache.org/) plugins that integrate with GitHub

## Downloads
Maven plugin that creates and uploads a built resource to be available as a
GitHub project download.

### Example
```xml
<build>
  <plugins>
    <plugin>
      <groupId>com.github.mojo</groupId>
      <artifactId>repository-downloads</artifactId>
      <executions>
        <execution>
          <configuration>
            <oauth2Token>...</oauth2Token>
          </configuration>
          <goals>
            <goal>upload</goal>
          </goals>
          <phase>install</phase>
        </execution>
      </executions>
    </plugin>
  </plugins>
</build>
```

#License
* [MIT License](http://www.opensource.org/licenses/mit-license.php)