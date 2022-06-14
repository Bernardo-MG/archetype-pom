# Archetype Parent POM

Parent [Maven POM][maven-pom-intro] setting up a [Maven Archetype][maven-archetype] project. This is done without adding any additional dependency to the project, only Maven plugins.

For a generic, non archetype, POM check the [base POM][base-pom].

## Features

- [Build validation][build-validation].
- [Maven Site reports][site-reports] added for the project.
- Common build and report [plugins][plugins-list].
- Deployment plugin prepared to deploy into the distribution management repo.
- Manifest prepared with default configuration.
- Sets the JDK version to be used by the project.
- Sets the project default encoding to UTF-8.

## Dependencies

The only dependencies included in the POM are the Maven plugins. No additional dependency is added.

## Example

The [Library Maven Archetype][library-archetype] makes use of this POM. And extends it. This is an easy way to check how the POM can be used and modified.

[maven-pom-intro]: https://maven.apache.org/guides/introduction/introduction-to-the-pom.html#Project_Inheritance
[base-pom]: https://github.com/Bernardo-MG/base-pom
[maven-archetype]: https://maven.apache.org/guides/introduction/introduction-to-archetypes.html

[library-archetype]: https://github.com/Bernardo-MG/library-maven-archetype

[build-validation]: ./build_validation.html
[site-reports]: ./site_reports.html
[plugins-list]: ./plugins_list.html
