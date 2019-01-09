# ngu-mvn-repo
NGU Maven repository


Install new JAR files:
mvn install:install-file -Dfile=[the jar file] -DgroupId=[the group id] -DartifactId=[the artifact id] -Dversion=1.0 -Dpackaging=jar

The JAR file is installed to the local .m2 repository.

Copy the folder into the releases folder and commit to github.

To use this repository in your own Maven project:
<repository>
      <id>ngu</id>
      <name>NGU Maven Repository</name>
      <url>https://github.com/ngu/ngu-mvn-repo/tree/master/releases/</url>
</repository>


* Rometools while we wait for https://github.com/rometools/rome/pull/409
