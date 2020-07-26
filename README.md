# Helidon Archetypes for static content support

```bash
Clone the github repository, then shift to root directory and run the following command:
mvn install

Now shift to a directory with no pre-existing pom.xml, and run the following command:
For SE:
mvn archetype:generate -DinteractiveMode=false -DarchetypeGroupId=io.helidon.archetypes -DarchetypeArtifactId=helidon-gt-se -DarchetypeVersion=2.0.1 -DgroupId=<groupid> -DartifactId=<artifactId> -Dpackage=<package>

For MP:
mvn archetype:generate -DinteractiveMode=false -DarchetypeGroupId=io.helidon.archetypes -DarchetypeArtifactId=helidon-gt-mp -DarchetypeVersion=2.0.1 -DgroupId=<groupid> -DartifactId=<artifactId> -Dpackage=<package>

Note: The last 3 flags are variables, set them according to your choice.

Your project has been generated!
```

