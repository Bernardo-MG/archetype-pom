# Plugins

## Build plugins

Used when creating the project artifacts.

Some are just included in the plugin management, there is no need to include them in the build explicitly.

- [Ant Run](https://maven.apache.org/plugins/maven-antrun-plugin/), can handle Ant scripts.
- [Archetype](http://maven.apache.org/archetype/maven-archetype-plugin/), creates new projects from a project template.
- [Assembly](http://maven.apache.org/plugins/maven-assembly-plugin/), uilds a distributable file from all the project components.
- [Clean](https://maven.apache.org/plugins/maven-clean-plugin/), cleans the output folder.
- [Compiler](https://maven.apache.org/plugins/maven-compiler-plugin/), compiles the source code.
- [Dependency](https://maven.apache.org/plugins/maven-dependency-plugin/), copies and manipulates the project dependencies.
- [Deploy](https://maven.apache.org/plugins/maven-deploy-plugin/), takes care of the deployment phase.
- [Enforcer](https://maven.apache.org/enforcer/maven-enforcer-plugin/), stops the project from being built if it does not comply with a set of rules
- [Install](https://maven.apache.org/plugins/maven-install-plugin/), installs the project into the local Maven repository.
- [Jar](https://maven.apache.org/plugins/maven-jar-plugin/), generates the jar file.
- [Release](https://maven.apache.org/maven-release/maven-release-plugin/), generates releases and updates the project.
- [Resources](https://maven.apache.org/plugins/maven-resources-plugin/), handles the project resources.
- [Site](https://maven.apache.org/plugins/maven-site-plugin/), generates the Maven Site.
- [Source](https://maven.apache.org/plugins/maven-source-plugin/), bundles the source into the packaged project.

## Report plugins

Some of these may be repeated from the build section. Which means they will build a report from artifacts generated during the build process.

- [Changes](https://maven.apache.org/plugins/maven-changes-plugin/), generates the changes report from the changes log.
- [Dependency](https://maven.apache.org/plugins/maven-dependency-plugin/), generates the dependencies analysis report.
- [Project Info](https://maven.apache.org/plugins/maven-project-info-reports-plugin/), generates general information reports.
- [Site](https://maven.apache.org/plugins/maven-site-plugin/), generates the Maven Site.
