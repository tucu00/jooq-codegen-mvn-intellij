# Sample Project Showing jOOQ-codegen/Maven/IntelliJ Issue

## Environment

* OSX 11.5.2
* OpenJDK 11.0.10+9
* Maven 3.5.3
* IntelliJ 2021.2.1 (Ultimate)

## Maven command

```$ mvn compile```

Compiles the project code, generates and compiles JPA model classes and jOOQ DSL classes.

## IntelliJ

Start from a 100% clean build, run ```mvn clean```.

Using IntelliJ build (without delegating to Maven) *Top Menu* -> *Build* -> *Rebuild*

Compiles the project code, generates and compiles JPA model classes. It does not generate jOOQ classes.
