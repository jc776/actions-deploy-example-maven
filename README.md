This package has a "Github Action" setup to build & deploy master under "Packages".
pom.xml specifies an exact repository name to use instead of the artifactId - see comment.

First attempt:
```
[WARNING] Could not transfer metadata io.github.jc776:maven-example:0.0.1-SNAPSHOT/maven-metadata.xml from/to github (https://maven.pkg.github.com/jc776/actions-deploy-example-maven): Not authorized
```
