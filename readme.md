# Archetype parent POM

Parent [Maven POM][maven-pom-intro] setting up a [Maven Archetype][maven-archetype] project. This contains the configuration for several plugins.

[![Maven Central](https://img.shields.io/maven-central/v/com.bernardomg.maven/archetype-pom.svg)][maven-repo]

[![Release docs](https://img.shields.io/badge/docs-release-blue.svg)][site-release]
[![Development docs](https://img.shields.io/badge/docs-develop-blue.svg)][site-develop]

## Features

- Reduces the need to set up new Maven archetype projects.
- Sets up the encoding and Java version of the project.
- Common build and report plugins.
- Validation rules, including dependency convergence.
- Basic configuration, such as a default manifest file.
- Support for JDK7 onward.
- Sets the project default encoding to UTF-8.

## Documentation

Documentation is always generated for the latest release, kept in the 'master' branch:

- The [latest release documentation page][site-release].

Documentation is also generated from the latest snapshot, taken from the 'develop' branch:

- The [the latest snapshot documentation page][site-develop].

The documentation site sources come along the source code (as it is a Maven site), so it is always possible to generate them using the following Maven command:

```
mvn site -P site,config
```

## Usage

The application is a XML file, a Maven POM file.

### Installing

The POM can be used by just adding the following lines to the Maven POM for your project:

```
<parent>
    <groupId>com.bernardomg.maven</groupId>
    <artifactId>archetype-pom</artifactId>
    <version>(Check POM or badges)</version>
</parent>
```

If needed, the project can be added to the local Maven repository with the following command:

```
mvn install -P config
```

## Collaborate

Any kind of help with the project will be well received, and there are two main ways to give such help:

- Reporting errors and asking for extensions through the issues management
- or forking the repository and extending the project

### Issues management

Issues are managed at the GitHub [project issues tracker][issues], where any Github user may report bugs or ask for new features.

### Getting the code

If you wish to fork or modify the code, visit the [GitHub project page][scm], where the latest versions are always kept. Check the 'master' branch for the latest release, and the 'develop' for the current, and stable, development version.

## License

The project has been released under the [MIT License][license].

[maven-pom-intro]: https://maven.apache.org/guides/introduction/introduction-to-the-pom.html#Project_Inheritance

[maven-repo]: http://mvnrepository.com/artifact/com.bernardomg.maven/archetype-pom
[issues]: https://github.com/Bernardo-MG/archetype-pom/issues
[license]: http://www.opensource.org/licenses/mit-license.php
[scm]: https://github.com/Bernardo-MG/archetype-pom
[site-develop]: https://docs.bernardomg.com/development/maven/archetype-pom
[site-release]: https://docs.bernardomg.com/maven/archetype-pom

[maven-archetype]: https://maven.apache.org/guides/introduction/introduction-to-archetypes.html
