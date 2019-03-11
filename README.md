# About this Repo

[![Build Status](https://travis-ci.com/soregums/base-ruby.svg?branch=master)](https://travis-ci.com/soregums/base-ruby)
[![Docker Pulls](https://img.shields.io/docker/pulls/soregums/base-ruby.svg)](https://hub.docker.com/r/soregums/base-ruby)
[![Docker Stars](https://img.shields.io/docker/stars/soregums/base-ruby.svg)](https://hub.docker.com/r/soregums/base-ruby)
[![Docker Layers](https://images.microbadger.com/badges/image/soregums/base-ruby.svg)](https://microbadger.com/images/soregums/base-ruby)

This repository is a fork of https://github.com/wodby/ruby with a few changes:

* Only Debian stretch slim (libv8 doesn't do muslc which is needed for mini_racer)
* Base image changed to `soregums/debian:stretch-slim`

## Docker Images

* Base image: [soregums/debian:stretch-slim](https://github.com/soregums/docker/debian/stretch/slim)
* [Docker Hub](https://hub.docker.com/r/soregums/base-ruby)

Supported tags and respective `Dockerfile` links:

* `2.6.1`, `2.6.1-dev` [_(Dockerfile 2.6)_]

[_(Dockerfile 2.6)_]: https://github.com/soregums/base-ruby/tree/master/2.6/stretch/Dockerfile.soregums

