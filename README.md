# jsdt-core

[![Release Build][ci_release_img]][ci_release_link]
[![Build][ci_img]][ci_link]
[![Maven Central][maven_img]][maven_link]
[![License][license_img]][license_link]

Forked from [revelc/jsdt-core] as there were incompatibility issues with the embedded [Google Guava] library and other libraries that needed a newer version of [Google Guava].

A small [Tycho] project which repackages the jsdt-core library from the
[Eclipse] project into a bundle to publish to [Maven Central] to use as a
dependency in other [Maven] projects, such as [formatter-maven-plugin].

[revelc/jsdt-core]: https://github.com/revelc/jsdt-core
[Google Guava]: https://github.com/google/guava
[Eclipse]: https://www.eclipse.org/
[Maven Central]: https://search.maven.org/
[Maven]: https://maven.apache.org/
[Tycho]: https://www.eclipse.org/tycho/
[ci_release_img]: https://github.com/funfried/jsdt-core/actions/workflows/release_maven.yml/badge.svg
[ci_release_link]: https://github.com/funfried/jsdt-core/actions/workflows/release_maven.yml
[ci_img]: https://github.com/funfried/jsdt-core/actions/workflows/maven.yaml/badge.svg
[ci_link]: https://github.com/funfried/jsdt-core/actions/workflows/maven.yaml
[formatter-maven-plugin]: https://github.com/funfried/formatter-maven-plugin
[license_img]: https://img.shields.io/badge/license-EPL%201.0-blue.svg
[license_link]: https://github.com/funfried/jsdt-core/blob/main/LICENSE
[maven_img]: https://maven-badges.herokuapp.com/maven-central/de.funfried.revelc.code.formatter/jsdt-core/badge.svg
[maven_link]: https://maven-badges.herokuapp.com/maven-central/de.funfried.revelc.code.formatter/jsdt-core
