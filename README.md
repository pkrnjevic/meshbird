DISCLAIMER: I dumped a lot of code without much documentation and optimization.
It needs to be cleaned up and better organized. Further work will be continued at
https://github.com/gyuho/runetcd.

<br>

# Meshbird ![Build Status](https://img.shields.io/travis/gophergala2016/meshbird.svg?style=flat-square)](https://travis-ci.org/gophergala2016/meshbird) [![Godoc](http://img.shields.io/badge/go-documentation-blue.svg?style=flat-square)](https://godoc.org/github.com/gophergala2016/meshbird)

Meshbird - distributed private networking. [Twitter](https://twitter.com/meshbird)

[![Build Status](https://travis-ci.org/gophergala2016/meshbird.svg)](https://travis-ci.org/gophergala2016/meshbird.svg)]

![Go Report Card](http://goreportcard.com/badge/gophergala2016/meshbird)

![MeshBird](https://avatars1.githubusercontent.com/u/16837838?v=3&s=600)

## Intro

Meshbird create distributed private networking between servers, containers, virtual machines and any computers in different datacenters, different countries, different cloud providers. All traffic transmit directly to recepient peer without passing any gateways. Meshbird do not require any centralized servers. Meshbird is absolutly decentralized distributed private networking.

For example, user can create private network between DigitalOcean's droplets in each datacenter and link it together by executing one command. All traffic will be encrypted with strong AES-256.

## Quick Start


```bash
$ go get github.com/gophergala2016/meshbird
````

```bash
$ meshbird new
```

```bash
$ MESHBIRD_KEY="<key>" meshbird join
```
