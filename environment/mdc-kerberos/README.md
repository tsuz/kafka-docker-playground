# Multi Data Center Kerberos

## Description

This is a deployment with no SSL encryption, and Kerberos GSSAPI authentication: it has 2 clusters: `europe` and `us`:

For each cluster, we have:

* 1 zookeeper
* 1 broker
* 1 connect


control-center is monitoring the two clusters

N.B: we have dedicated zookepper and broker for metrics.

## How to run

Simply run:

```
$ just use <playground run> command and search for start.sh in this folder
```
