# Changelog

## 0.3.0 (unreleased)

  - Directives now clean existing CORS-related headers when responding to an actual request (#28).
  - Support `Origin: null` in simple/actual requests (#31).
  - The `CorsRejection` class has been refactored to be cleaner.
  - Update Scala to 2.12.4 and 2.11.12.
  - Update akka-http to 10.1.0, removal of Akka 2.4 support (#34).

### Migrate from 0.2 to 0.3

  - Custom rejection handlers must be updated to reflect the new `CorsRejection` class.

## 0.2.2 (2017-09-25)

  - Update Scala to 2.12.3 and 2.11.11.
  - Update akka-http to 10.0.10.
  - Update sbt to 1.0.x major release.

## 0.2.1 (2017-04-03)

  - Add Java API (#8)
  - Update akka-http to 10.0.5.
  
### Migrate from 0.1 to 0.2
The API remains the same, but classes have moved in new packages to accommodate the Java API.

  - Directives are now in `ch.megard.akka.http.cors.scaladsl`;
  - Models are now in `ch.megard.akka.http.cors.scaladsl.model`;
  - Settings are now in `ch.megard.akka.http.cors.scaladsl.settings`.

## 0.1.11 (2017-01-31)

  - Update Scala to 2.12.1.
  - Update akka-http to 10.0.3.

## 0.1.10 (2016-11-23)

  - Update akka-http to 10.0.0.

## 0.1.9 (2016-11-10)

  - Cross compile with Scala 2.12.0.
  - Update akka-http to 10.0.0-RC2.

## 0.1.8 (2016-10-30)

  - Cross compile with Scala 2.12.0-RC2.

## 0.1.7 (2016-10-02)

  - Cross compile with Scala 2.12.0-RC1.
  - Update Akka to 2.4.11.

## 0.1.6 (2016-09-10)

  - Update Akka to 2.4.10.

## 0.1.5 (2016-08-24)

  - Update Akka to 2.4.9.
  - Update sbt to 0.13.12.

## 0.1.4 (2016-07-08)

  - Update Akka to 2.4.8.

## 0.1.3 (2016-07-08)

  - Update Akka to 2.4.7.

## 0.1.2 (2016-05-11)

  - Update Akka to 2.4.4.
  - Add benchmarks with results in README.

## 0.1.1 (2016-04-07)

  - Update Akka to 2.4.3.

## 0.1.0 (2016-03-20)

Initial release.
