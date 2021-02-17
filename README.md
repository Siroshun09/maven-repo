# maven-repo

Bintray (JCenter) の閉鎖に伴い、公開済みの成果物を退避させたリポジトリ。

新しいバージョンからは Maven Central にデプロイ予定。

This is the repository where the public artifacts have been moved due to the closure of Bintray (JCenter).

The new version will be deployed to Maven Central.

## Repository

```xml
  <repository>
    <id>siroshun09-github-maven-repo</id>
    <url>https://siroshun09.github.io/maven-repo</url>
  </repository>
```

```build.gradle
  maven {
    url "https://siroshun09.github.io/maven-repo"
  }
```

## Libraries

- [ConfigAPI](https://github.com/Siroshun09/ConfigAPI)
- [Event4J](https://github.com/Siroshun09/Event4J)
- [MCCommand](https://github.com/Siroshun09/MCCommand)
- [MCMessage](https://github.com/Siroshun09/MCMessage)
