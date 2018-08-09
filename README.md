# GoBeansproxy [![Build Status](https://travis-ci.org/douban/gobeansproxy.svg?branch=master)](https://travis-ci.org/douban/gobeansproxy)

A proxy for [Gobeansdb](https://github.com/douban/gobeansdb).

# Prepare

GoBeansDB use `vgo` manage dependencies, please install vgo first.

## Install

```
$ cd ${GOPATH}
$ git clone http://github.com/douban/gobeansproxy.git src/github.com/douban/gobeansproxy
$ cd src/github.com/douban/gobeansproxy
$ make
```

## test

```
$ make test  # unit test
```

## run

```
$ ${GOPATH}/bin/proxy -h
```
