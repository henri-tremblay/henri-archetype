# henri-archetype

An improvement over the default maven-archetype-quickstart that is slowly getting old.

The improvements are:
* Default is Java 11
* JUnit 5
* AssertJ added

So nothing wild but I was tired of modifying the quickstart all the time.

## To use
 
Just install locally 

`mvn install`

and then select it when generating a project

`mvn archetype:generate -Dfilter=henri=archetype`

## To check dependencies and plugins versions

`mvn versions:display-dependency-updates versions:display-plugin-updates`