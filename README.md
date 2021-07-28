# java-cli-buckbuild-hello-world

## Description
A POC for buck build, which does
C, CPP, C#, Golang, Groovy, Java,
Kotlin, Python, Rust, and Scala.
Buck seems to extend the ant build tool
so by default it supports C, CPP, and
Java out-of-the-box.

## Tech stack
- java
  - >=1.8
- buck
  - ant >=1.9
  - watchman
  - python 2.7

## Docker stack
- praqma/native-buck

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credits
- [Buck sample] (https://github.com/orrsella/buck.git)
- [Buck home] (https://buck.build/setup/getting_started.html)
- [Docker image] (https://hub.docker.com/r/praqma/native-Buck)
