# scalapb-circe [![Build Status](https://travis-ci.org/scalapb-json/scalapb-circe.svg?branch=master)](https://travis-ci.org/scalapb-json/scalapb-circe)

The structure of this project is hugely inspired by [scalapb-json4s](https://github.com/scalapb/scalapb-json4s)

## Dependency

Include in your `build.sbt` file

```scala
libraryDependencies += "io.github.scalapb-json" %% "scalapb-circe" % "0.1.3"
```

for scala-js

```scala
libraryDependencies += "io.github.scalapb-json" %%% "scalapb-circe" % "0.1.3"
```

## Usage

There are four functions you can use directly to serialize/deserialize your messages:

```scala
JsonFormat.toJsonString(msg) // returns String
JsonFormat.toJson(msg) // returns Json

JsonFormat.fromJsonString(str) // return MessageType
JsonFormat.fromJson(json) // return MessageType
```

### Credits

- https://github.com/whisklabs/scalapb-playjson
- https://github.com/scalapb/scalapb-json4s
