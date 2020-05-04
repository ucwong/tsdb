# TSDB 

## THIS PROJECT IS BEING MOVED TO PROMETHEUS REPOSITORY: https://github.com/prometheus/prometheus/pull/5805

[![Build Status](https://travis-ci.org/ucwong/tsdb.svg?branch=master)](https://travis-ci.org/ucwong/tsdb)
[![GoDoc](https://godoc.org/github.com/ucwong/tsdb?status.svg)](https://godoc.org/github.com/ucwong/tsdb)
[![Go Report Card](https://goreportcard.com/badge/github.com/ucwong/tsdb)](https://goreportcard.com/report/github.com/ucwong/tsdb)

This repository contains the Prometheus storage layer that is used in its 2.x releases.

A writeup of its design can be found [here](https://fabxc.org/blog/2017-04-10-writing-a-tsdb/).

Based on the Gorilla TSDB [white papers](http://www.vldb.org/pvldb/vol8/p1816-teller.pdf).

Video: [Storing 16 Bytes at Scale](https://youtu.be/b_pEevMAC3I) from [PromCon 2017](https://promcon.io/2017-munich/).

See also the [format documentation](docs/format/README.md).
