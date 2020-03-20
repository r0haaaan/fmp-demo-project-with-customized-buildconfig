# Random Generator

This is a simple random number generation application which just generates a random string on `/random` endpoint.

## How to build
Just run `mvn clean install`

## How to run
Do `mvn spring-boot:run`

After spring boot initializes, just do a `curl localhost:8080/random` to check endpoint.

## How to build Docker image / S2I build

Do `mvn fabric8:build`

## How to generate and deploy Kubernetes/Openshift artifacts onto Kubernetes/Openshift cluster

Do `mvn fabric8:resource fabric8:deploy`
