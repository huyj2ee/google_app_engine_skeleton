# Google App Engine Skeleton
A skeleton project to build spring boot application that is runned on Google App Engine standard environment with thymeleaf library is imported.


# Usage:
## Process in detail
* To rebuild a package that running on local machine:
    * Build: mvn -f localpom.xml clean package
    * Test: java -jar target/gae-skeleton-0.0.1-SNAPSHOT.jar

* To build and deploy application running on Google App Engine standard environment:
    * Build and deploy: mvn appengine:deploy
## Import application
The skeleton could be upgraded to some simple utilities. Please see README.TXT in folder upgrade for more detail.


