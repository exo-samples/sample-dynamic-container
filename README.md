sample-dynamic-container
========================


How to compile this project ?
----------------

First of all you must have [git installed](http://git-scm.com/book/en/Getting-Started-Installing-Git) on your computer.

```
git clone git@github.com:exo-samples/sample-dynamic-container.git
```

you can open the project within your terminal and build the sources

```
mvn clean install
```

you will find 2 modules compiled the Sample Extension Configuration and the Sample Portlet War.


How to installed this sample ?
----------------

You are now in possession of one war and on that must be dropped in your eXo platform standalone.
* Place your jar in --> platform-4.1.x/lib
* Place your war in --> platform-4.1.x/webapps

Then you just have to start your platform!