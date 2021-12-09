# java-cli-maven-spring-surefire-pmd-cucumber-junit-car-data

## Description
A POC for spring app using JUnit5
and cucumber framework with surefire
and pmd plugin.
Define a parameter type of `example.model.Car`
in the test runner class.

## Tech stack
- java
- maven
  - spring
  - junit
  - surefire
  - cucumber
  - pmd

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- pmd report found at bin/target/site

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept](https://stackoverflow.com/questions/67847818/maven-junit-5-cucumber-not-running-tests)
- [Parameter Type code base](https://thepracticaldeveloper.com/cucumber-guide-3-step-definitions-state/)
