# markdown2sqlite project

Motivation:
Project to convert markdown files into SQLite database, useful when people need to
track/query big number of markdown files.

Tech stack:
 * Java 11
 * Quarkus
 * Sqlite
 * Flyway

# Development

Building project:
```
./gradlew build
```

Native project run:

```
./gradlew quarkusDev --quarkus-args='Potato'
```

Fat jar building:
```
./gradlew build -Dquarkus.package.type=uber-jar
```

Native application building:
```
./gradlew build -Dquarkus.package.type=native
```