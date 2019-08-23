# demos-common 
Project containing various JVM projects used by Confluent, Inc demos and examples.

# prerequisites
* bash
* make
* grep

# usage
The repository has a `Makefile` which follows a standard target naming convention for cleaning, building, testing and packaging.
To see the various targets and supporting help text try:
```
make help
```

# Publishing Docker Image
To release a new version and publish a new docker image run (docker daemon must be logged into proper Docker Hub account):
```
make publish
```
