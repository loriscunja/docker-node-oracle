# docker-node-oracle


Docker image to be used for building a container ready with Oracle instant client binaries and all necessary environment variables needed to use the primary Node.js Oracle Database driver libraries:

[node-oracledb](https://github.com/oracle/node-oracledb)


## Components

[Official Node 8 Docker Image](https://hub.docker.com/_/node/)

[Oracle Instant Client 12.2](http://www.oracle.com/technetwork/topics/linuxx86-64soft-092277.html)

## Usage

Within your Dockerfile:

```
FROM vitorveiga/docker-node-oracle:8
```