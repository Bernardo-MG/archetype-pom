# Parent POMs

Parent [Maven POM][maven-pom-intro] files take care of setting up common configuration which can be inherited by any Maven project.

In this case it prepares several build and report plugins for the project, and also sets it up with a configuration based on various good practices, such as testing or dependency convergence.

All this configuration helps to prepare a [Maven Archetype][maven-archetype] project, and is not meant to any other type of project, even if it is generic enough to be reused for them.

If a a completely generic POM is needed the [base POM][base-pom] project is a better option.

## Features

- [Build validation][build-validation].
- [Maven Site reports][site-reports] added for the project.
- Common build and report [plugins][plugins-list].
- Deployment plugin prepared to deploy into the distribution management repo.
- Manifest prepared with default configuration.
- Sets the JDK version to be used by the project.
- Sets the encoding (UTF-8 by default) for all the project.

## Dependencies

The only dependencies included in the POM are the Maven plugins. No additional dependency is added.

## Archetype using the POM

The [Library Maven Archetype][library-archetype] makes use of the base POM. It is a useful way to check how the POM can be used and modified.

[maven-pom-intro]: https://maven.apache.org/guides/introduction/introduction-to-the-pom.html#Project_Inheritance
[maven-archetype]: https://maven.apache.org/guides/introduction/introduction-to-archetypes.html

[library-archetype]: https://github.com/Bernardo-MG/library-maven-archetype

[build-validation]: ./build_validation.html
[site-reports]: ./site_reports.html
[plugins-list]: ./plugins_list.html

[base-pom]: https://github.com/Bernardo-MG/base-pom
