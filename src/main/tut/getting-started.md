# Getting Started

@@@ note
Most of the examples are shown using the Spark DataFrames API. However, many could also be rewritten to use the Spark SQL API instead. We hope to add more examples in that form in the future.
@@@

## sbt configuration

*RasterFrames* is published via Bintray's JCenter server, which is one of the default sbt resolvers. To use, just add the following library dependency:

sbt:

```scala
libraryDependencies += "io.astraea" %% "raster-frames" % "x.y.z"
```

Maven:

```
<dependency>
  <groupId>io.astraea</groupId>
  <artifactId>raster-frames</artifactId>
  <version>x.y.z</version>
</dependency>
```

@@@ note

*Coming soon*: We'll soon be providing a new project template to streamline the process of getting
started with *RasterFrames* 

@@@