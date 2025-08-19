# java-template

`java-template` is a Maven archetype designed to quickly scaffold new Java Maven projects.  
It provides a clean starting point with recommended structure and dependencies.

## Features

- Standard Maven project layout
- Pre-configured dependencies (JUnit, Lombok, etc.)
- Ready for Java 21 (or configurable)
- Easy to extend for your own needs

## Usage

After publishing to Maven Central, you can generate a new project using:

```shell
mvn archetype:generate \
  -DarchetypeGroupId=com.yourorg \
  -DarchetypeArtifactId=java-template \
  -DarchetypeVersion=1.0.0
```

## Publishing

This archetype will be published to Maven Central for public use.

## License

MIT