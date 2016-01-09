Docker Voting App
=================

This is based on the [example voting app](https://github.com/docker/example-voting-app) with multiple services. 

Architecture
-----

* A Python webapp which lets you vote between two options
* A Redis queue which collects new votes
* A Java worker which consumes votes and stores them in…
* A Postgres database backed by a Docker volume
* A Node.js webapp which shows the results of the voting in real time
