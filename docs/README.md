# Pouch Document

Pouch Docs is written, drawn, memorialized representation of all things about Pouch. For those who are generally interested in Pouch, README.md of this repo is sufficient. While if you wish to take advantage of Pouch to create more innovative value, docs here would be strong support for that.

Organization of document is as following:

* [Features](#features)
* [Get Started](#get-started)
* [Commandline](#commandline)
* [API](#api)
    * [HTTP API](#http-api)
    * [HTTP API changelog](#http-api-changelog)
    * [CRI gRPC API](#grpc-api)
    * [CRI gRPC changelog](#grpc-api-changelog)
* [Contributions](#contributions)
* [Test Guide](#test-guide)
* [Underlying Tech](#underlying-tech)
* [Static Files](#static-files)

## Features

[Features](features) contains all features of Pouch. To enable a satisfying environment for user's applications, Pouch provides plenty of features, such as strong-isolation technology including hyper-based containers and lxcfs-base resource view isolation, rich container, P2P image distribution and so on. For more aspects, TLS-based security, prometheus supporting and more features also help Pouch be adoptive for enterprises. In addition, in all the document we illustrate what is the best scenario of the corresponding feature. 

## Get Started

[Get Started](../INSTALLATION.md) is exactly what you need if you would give Pouch a try. This document includes what are the prerequisites, how to install Pouch and how to experience Pouch.

## Commandline

For almost all of users, [commandline](./commandline) is the first reference you may need. Document in directory commandline is about command detailed usage of pouch cli. You can get introductions, synopsis, examples, options about command. Last but not least, pouch can guarantee commandline docs is strongly consistent with pouch cli's source code. What's more, all commandline docs are auto generated via source code.

## API

Commandline is the easiest way to extend Pouch's ability. And API extension will bring more powerful experience for users. 

### HTTP API

Document [HTTP-API.md](api/HTTP_API.md) contains all raw HTTP API details. For Pouch's HTTP API, it is all recorded in file [swagger.yml](../apis/swagger.yml). The document HTTP_API.md is also auto generated by swagger.yml. So, we can still guarantee the strong consistency between code implementation and HTTP API document.

### HTTP API Changelog

Document [HTTP-API-CHANGELOG.md](api/HTTP_API_CHANGELOG.md) contains HTTP API changelog. In principle, HTTP API of Pouch should always keep still even if more versions are released. However, when pouch evolves, more functionality, direction adjustment and bugfix in API would make HTTP API change, and we pouch provides HTTP API changelog to track all the evolution.

### gRPC API

Document [GRPC-API.md](api/GRPC_API.md) contains all raw gRPC API details. Pouch can be run as a native container engine to support CRI and CRI ability is exposed via gRPC.

### gRPC API Changelog

Document [GRPC-API-CHANGELOG.md](api/GRPC_API_CHANGELOG.md) contains GRPC API changelog. In principle, gRPC API of Pouch should always keep still even if more versions are released. However, when pouch evolves, more functionality, direction adjustment and bugfix in API would make gRPC API change, and we pouch provides gRPC API changelog to track all the evloving.

## Test Guide

[Test Doc](test) is the best reference helping contributors get aware of how to setup testing environment and do it. Currently we can divide test of Pouch into four dimensions: unit test, integration test of API and CLI, and CRI validation test. For more details, please refer to [test](test).

## Contributions

[Contributions](contributions) is a helpful document for community participants to learn how to contribute and coordinate within Pouch open source project. We draw up some friendly guidance for all participants.

## Underlying Tech

[Underlying Tech](underlying_tech) helps users to get more knowledge about the underlying technology adopted in Pouch, such as cGroup, Namespce technology in Linux Kernel, hypervisor-based container technology, lxcfs, and so on. If users wish to master Pouch technology better, this document is a must-read.

## Static Files

[Static files](static_files) contains all static files for Pouch. If users are seeking some material in particular, such as Pouch log, architecture of it, or more pic about pouch. This document directory is where users need a try.
