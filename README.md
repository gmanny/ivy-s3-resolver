ivy-s3-resolver
===============

Ivy resolver that supports publishing to S3 objects.

To add a dependency in your sbt project use this:

```scala
resolvers += "Era7 maven releases" at "http://releases.era7.com.s3.amazonaws.com"

libraryDependencies += "ohnosequences" % "ivy-s3-resolver" % "<version>"
```

(see the latest version in the [releases list](https://github.com/ohnosequences/ivy-s3-resolver/releases))

Normally you won't use this resolver directly, see [sbt-s3-resolver](https://github.com/ohnosequences/sbt-s3-resolver) instead.


API documentation
-----------------

Just in case, API docs for 

- [`v0.5.0`](http://ohnosequences.com/ivy-s3-resolver/docs/api/0.5.0/)
- [`v0.6.0`](http://ohnosequences.com/ivy-s3-resolver/docs/api/0.6.0/)


### Contacts

This project is maintained by [@evdokim](https://github.com/evdokim).
