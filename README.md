# henri-archetype

An improvement from the default maven-archetype-quickstart that is slowing getting old.

The improvements are:
* Default is Java 8
* JUnit 4
* AssertJ added

So nothing wild but I was tired of modifying the quickstart all the time.

## To use
 
Just install locally 

`mvn install`

and the select it when generating a project

`mvn archetype:generate -Dfilter=henri=archetype`
