Spring Boot Release Demo
====

This demo project uses the
[Axion Release Gradle plugin](https://github.com/allegro/axion-release-plugin) for a Spring Boot project.

## Basic usage

```
$ git tag
<empty list>

$ ./gradlew currentVersion
0.1.0-SNAPSHOT

$ ./gradlew release

$ git tag
release-0.1.0

$ ./gradlew cV
0.1.0

$ git add -A && git commit -m "Updates something" && ./gradlew release

$ git tag
release-0.1.0
release-0.1.1

$ ./gradlew cV
0.1.1
```

## Documentation

Documentation is available at [axion-release read the docs](https://readthedocs.org/docs/axion-release-plugin/en/latest).