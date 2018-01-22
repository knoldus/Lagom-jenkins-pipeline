# Lagom-jenkins-pipeline

This project contains a Lagom microservice which contains a simple pathCall to understand how a Lagom microservice works.
This project is taken as an example for Jenkins Integration. You can find all the Jenkins settings in `Jenkinsfile`, which is in the root directory.

## Compile

`mvn clean complie`

## Test

`mvn clean test`
  
 ## Verify
 
`mvn clean verify`

## Run

`mvn lagom:runAll`

## Continuous Integration

`Jenkinsfile` contains all the stages to build the given project.
