# This is Project Site Main Page

The project can be used as a template for multi-module Java project with working
mvn generated site.

## Included reports
* JavaDocs [maven-javadoc][1]
* Source code cross-reference [maven-jxr][2]
* Unit and integration tests results [maven-surefire][3], [maven-failsafe][4]
* Coding style conventions compliance [maven-checkstyle][5]
* Tests code coverage [jacoco-maven][6]

[1] : http://maven.apache.org/plugins/maven-javadoc-plugin/
[2] : http://maven.apache.org/plugins/maven-jxr-plugin/
[3] : http://maven.apache.org/surefire/maven-surefire-plugin/
[4] : http://maven.apache.org/surefire/maven-failsafe-plugin/
[5] : http://maven.apache.org/plugins/maven-checkstyle-plugin/
[6] : http://www.eclemma.org/jacoco/trunk/doc/maven.html

## Known bugs and limitations
* Tests coverage reports are not aggregated
* Coding style reports for tests have broken source code links
* Coding style report plugin currently does not support Java 8 lambda functions
