Consider switching to [Java EE 8 Essentials Archetype](https://github.com/AdamBien/javaee8-essentials-archetype)

A Plain and Clean JavaEE 7 Maven Archetype
=====================

This artifact is installed in the maven central repository and can be automatically installed using the
mvn archetype:generate (in batch mode -B) invocation:

`mvn archetype:generate -B -DarchetypeGroupId=com.airhacks -DarchetypeArtifactId=javaee7-essentials-archetype -DarchetypeVersion=1.4-SNAPSHOT -DgroupId=your.package -DartifactId=your-project-name -Dversion=1.0-SNAPSHOT`

Build project and deploy to your JavaEE 7 application server.
Opening browser with URL http://localhost:8080/your-project-name/resources/ping should prompt "Enjoy JavaEE 7!".

Choose the version v1.4 if you like to have beans.xml and JAXRSConfiguration included and v1.2 for a plain Java EE project.
