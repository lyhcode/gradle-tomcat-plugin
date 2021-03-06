### Version 0.8 (October 22, 2011)

* Introduced configuration for Tomcat libraries. **Note: Do not configure them in the `buildscript` closure anymore!**
* All tasks now extend `org.gradle.api.DefaultTask`.
* Support for exposing a HTTPS connector - [Issue 10](https://github.com/bmuschko/gradle-tomcat-plugin/issues/10).

### Version 0.7 (May 3, 2011)

* Support Tomcat 7 - [Issue 7](https://github.com/bmuschko/gradle-tomcat-plugin/issues#issue/7).
* Separated code into modules.
* Embedded Tomcat runs in its own classloader to avoid library conflicts with provided Gradle plugins.
* Added unit tests.

### Version 0.6 (March 30, 2011)

* Support configurable context.xml - [Issue 6](https://github.com/bmuschko/gradle-tomcat-plugin/issues#issue/6).

### Version 0.5 (March 10, 2011)

* Support for running Tomcat as daemon - [Issue 5](https://github.com/bmuschko/gradle-tomcat-plugin/issues#issue/5).

### Version 0.4 (March 5, 2011)

* Support configurable root context path - [Issue 4](https://github.com/bmuschko/gradle-tomcat-plugin/issues#issue/4).
* Added license file.

### Version 0.3 (December 19, 2010)

* Added optional configuration property `URIEncoding`.
* Set default VCS to Git for Gradle IDEA plugin.

### Version 0.2 (December 8, 2010)

* Added optional configuration property `additionalRuntimeJars`.
* Refactored some code.
* Wrote some unit tests.

### Version 0.1 (December 2, 2010)

* Initial release.