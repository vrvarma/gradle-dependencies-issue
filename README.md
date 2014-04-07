gradle-dependencies-issue
=========================

When you run gradlew cleanEclipse eclipse in gradle-1.11 it doesnt generate the correct dependencies.

if you check src/modules/discovery/container/common/.classpath

you would see that it has the following entry

<classpathentry kind="src" path="/discovery-container-common" exported="true"/>

Works fine with gradle-1.10..