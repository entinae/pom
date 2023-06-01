# Changes by Version

## [v1.0.6-SNAPSHOT](https://github.com/entinae/pom/compare/6b2db72d18fdb56f5ffc1951dd1dc6778bb67555..HEAD)

## [v1.0.5](https://github.com/entinae/pom/compare/5983e42306d93274eb9549a00f978f86fed20b6b..6b2db72d18fdb56f5ffc1951dd1dc6778bb67555) (2020-05-23)
* Add `itestCompile` and `jmh` profiles.
* Add default `retryFailedDeploymentCount=3` to `maven-deploy-plugin` configuration.
* Dowgrade `org.apache.maven.plugins:maven-resources-plugin` from `v3.1.0` to `v2.7` to resolve symlink issues.

## [v1.0.4](https://github.com/entinae/pom/compare/36514801954ffee27a56fdf9722cda0b4036db24..5983e42306d93274eb9549a00f978f86fed20b6b) (2019-07-21)
* Fix `maven-invoker-plugin` pattern for plugin testing.
* Switch from `org.eluder.coveralls:coveralls-maven-plugin` to `org.safris.maven:coverallsio-maven-plugin`.
* Upgrade `org.safris.maven:javadocio-maven-plugin:0.1.0` to `0.1.1`.
* Upgrade `org.openjax.jaxb:jaxb-maven-plugin:0.8.1` to `0.8.2`.
* Upgrade `org.openjax.xml:xml-maven-plugin:0.9.2` to `0.9.3`.
* Upgrade `org.mockito:mockito-core:2.27.0` to `3.0.0`.

## v1.0.3 (2019-05-12)
* Initial public release.