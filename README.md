# Starter Maven Archetype for Funcatron

A [Maven](http://maven.apache.org/) [Archetype](http://maven.apache.org/components/archetype/maven-archetype-plugin/)
that makes it super easy for a Java developer to get started with
Funcatron.

To use the archetype:

```
mvn archetype:generate  \
   -DarchetypeGroupId=funcatron \
   -DarchetypeArtifactId=starter \
   -DarchetypeVersion=0.1.0 \
   -DgroupId=my.stellar \
   -DartifactId=thang \
   -DarchetypeRepository=https://clojars.org/repo
```

To run the Funcatron dev server:

```
docker run -ti --rm  -p 3000:3000 -p 54657:54657 funcatron/dev-docker:latest
```

## Contributing

Please see [CONTRIBUTING](https://github.com/funcatron/tron/blob/master/CONTRIBUTING.md) for details on
how to make a contribution.

## Licenses and Support

Funcatron is licensed under an Apache 2 license.

Support is available from the project's founder,
[David Pollak](mailto:funcmaster-d@funcatron.org).
