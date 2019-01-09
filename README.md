# ngu-mvn-repo
NGU Maven repository


Install new JAR files:
mvn install:install-file -Dfile=[the jar file] -DgroupId=[the group id] -DartifactId=[the artifact id] -Dversion=1.0 -Dpackaging=jar

The JAR file is installed to the local .m2 repository.

Copy the folder into the releases folder and commit to github.

To use this repository in your own Maven project:

&lt;repository>      
&lt;id>ngu&lt;/id>    
&lt;name>NGU Maven Repository&lt;/name>    
&lt;url>https://github.com/ngu/ngu-mvn-repo/tree/master/releases/ &lt;/url>
&lt;/repository>


* Rometools while we wait for https://github.com/rometools/rome/pull/409
