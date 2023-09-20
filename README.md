## Steps to Run
I used a docker container to bypass all the Windows and corporate help.
1. ```./gradlew clean war```
1. ```docker pull tomcat```
1. ``` docker run -d -v <ABSOLUTE_PATH_TO>\demo\build\libs:/usr/local/tomcat/webapps  --rm --name tc10 -p 8888:8080 tomcat:10.1 ```

[Bask in the glory of the new service](http://localhost:8888/demo-0.1/hello)

## Resources
- [Micronaut Servlet](https://micronaut-projects.github.io/micronaut-servlet/latest/guide/index.html)
- [Repository](https://github.com/micronaut-projects/micronaut-servlet)
- [Apache Tomcat Offical Image](https://hub.docker.com/_/tomcat)

## Micronaut 4.1.1 Documentation

- [User Guide](https://docs.micronaut.io/4.1.1/guide/index.html)
- [API Reference](https://docs.micronaut.io/4.1.1/api/index.html)
- [Configuration Reference](https://docs.micronaut.io/4.1.1/guide/configurationreference.html)
- [Micronaut Guides](https://guides.micronaut.io/index.html)
---

- [Shadow Gradle Plugin](https://plugins.gradle.org/plugin/com.github.johnrengelman.shadow)
- [Micronaut Gradle Plugin documentation](https://micronaut-projects.github.io/micronaut-gradle-plugin/latest/)
- [GraalVM Gradle Plugin documentation](https://graalvm.github.io/native-build-tools/latest/gradle-plugin.html)
## Feature micronaut-aot documentation

- [Micronaut AOT documentation](https://micronaut-projects.github.io/micronaut-aot/latest/guide/)


## Feature tomcat-server documentation

- [Micronaut Tomcat Server documentation](https://micronaut-projects.github.io/micronaut-servlet/1.0.x/guide/index.html#tomcat)


## Feature serialization-jackson documentation

- [Micronaut Serialization Jackson Core documentation](https://micronaut-projects.github.io/micronaut-serialization/latest/guide/)


## Feature jdbc-tomcat documentation

- [Micronaut Tomcat JDBC Connection Pool documentation](https://micronaut-projects.github.io/micronaut-sql/latest/guide/index.html#jdbc)


## Feature http-client documentation

- [Micronaut HTTP Client documentation](https://docs.micronaut.io/latest/guide/index.html#nettyHttpClient)


