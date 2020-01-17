# keios-dynabuffers

Hodgepodge of [dynabuffers](https://github.com/leftshiftone/dynabuffers) schemata used for keios inter-process-communication between polyglot systems. 
Formerly known as [keios-protocol](https://github.com/leftshiftone/keios-protocol)

### Release

Currently only manual release is possible:

**JVM**

_requires bintray credentials_

`./gradlew clean build bintrayUpload`

**Python**

_required pypi.org credentials_

```$sh
$ cd atlas
$ poetry version minor
$ poetry build && poetry publish
```
