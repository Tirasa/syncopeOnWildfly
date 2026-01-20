# Run Apache Syncope on Wildfy

Practical implementation of official advices at Syncope [documentation](https://syncope.apache.org/docs/4.0/reference-guide.html#wildfly-38).

## How to test ##

This projects assumes that you have [Apache Maven 3.9.9](http://maven.apache.org) and Docker with Compose plugin installed

#### clone ####

<pre>
$ git clone git://github.com/Tirasa/syncopeOnWildfly.git
</pre>

#### build ####

<pre>
$ cd syncopeOnWildfly
$ mvn clean package
$ docker compose up
</pre>

## test ##

 1. Syncope Core is available at http://localhost:8080/syncope/
 1. Syncope Console is available at http://localhost:28080/syncope-console/
 1. Syncope Enduser is available at http://localhost:38080/syncope-enduser/

## Need more info or commercial support? ##
Just drop an [e-mail](mailto:syncope@tirasa.net).
