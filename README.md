# scala-web-bloop-sbt-play-api-html-hello-world

## Description
A call to playframework web api
with a value and readers html file.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- scala
- bloop-sbt
  - play

## Docker stack
- hseeberger/scala-bloop-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10

## To run
`sudo ./install.sh -u`
End points
- http://localhost
- curl -X PUT localhost/message
- curl -X PUT localhost/John

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code based on](https://www.baeldung.com/java-intro-to-the-play-framework)
