# Micronaut Zeebe Example

This example shows how to implement a Zeebe Worker based on the Micronaut Framework using
the [Micronaut Zeebe Client](https://github.com/camunda-community-hub/micronaut-zeebe-client).

## Configuration

Add your credentials to access Camunda Cloud (or your self hosted cluster) to `application.yml`.

## Worker

To start the worker:

`./gradlew run`

This will output something like:

```
Hello world, from job 2251799813685345
Activated 1 jobs for worker default and job type say-goodbye
Retrieved value 40. Goodbye, from job 2251799813685352
Activated 1 jobs for worker default and job type say-hello
```

## GraalVM

See https://github.com/camunda-community-hub/micronaut-zeebe-client#graalvm for generic instructions.
