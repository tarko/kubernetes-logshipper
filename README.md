kubernetes-logshipper
=====================

Simple utility for shipping container logs from kubernetes workers to syslog server in JSON format and UDP.

Usage
=====

```
logshipper -l /var/log/containers/ -h syslog.server -p 5147
```
