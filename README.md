This package has a "Github Action" setup to build & deploy master under "Packages".
pom.xml specifies an exact repository name to use instead of the artifactId - see comment.

First attempt:
```
[WARNING] Could not transfer metadata io.github.jc776:maven-example:0.0.1-SNAPSHOT/maven-metadata.xml from/to github (https://maven.pkg.github.com/jc776/actions-deploy-example-maven): Not authorized
```
Second attempt:
```
Failed to execute goal org.apache.maven.plugins:maven-deploy-plugin:2.7:deploy (default-deploy) on project maven-example: Failed to deploy artifacts: Could not transfer artifact io.github.jc776:maven-example:jar:0.0.1 from/to github (https://maven.pkg.github.com/jc776/actions-deploy-example-maven): Failed to transfer file https://maven.pkg.github.com/jc776/actions-deploy-example-maven/io/github/jc776/maven-example/0.0.1/maven-example-0.0.1.jar with status code 401 ->
```
