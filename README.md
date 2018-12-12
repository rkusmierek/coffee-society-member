# CoffeeSociety Member Service
[![Build Status](https://travis-ci.org/rkusmierek/coffee-society-member.svg?branch=master)](https://travis-ci.org/rkusmierek/coffee-society-member)

## Building

To execute complete building process (jar and docker image), execute command:

```
make
```

If you want to build only a jar-file (skip building docker image), type:

```
make build-jar
```

To build docker image (assuming you have already built a jar-file), type:

```
make build-docker
```

## Running

To run this service, execute command:

```
make run-jar
```

If you want to run this service in a container:

```
make run-docker
```
