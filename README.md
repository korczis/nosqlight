# NoSQLight

Small easily embeddable Document Oriented DB for everyday use.

Think about it as about NoSQL version of SQLite.

## Requirements

* Open Source - BSD, MIT will be the best
* Multiarch (x86, amd64, arm at least)
* [Self-contained](https://sqlite.org/selfcontained.html) - It requires very minimal support from external libraries or from the operating system.
* [Serverless](https://sqlite.org/serverless.html) - database reads and writes directly from the database files on disk. There is no intermediary server process.
* [Zero-Configuration](https://sqlite.org/zeroconf.html) - 
  * DB does not need to be "installed" before it is used. 
  * There is no "setup" procedure. 
  * There is no server process that needs to be started, stopped, or configured. 
  * There is no need for an administrator to create a new database instance or assign access permissions to users. 
  * DB uses no configuration files. 
  * Nothing needs to be done to tell the system that DB is running. 
  * No actions are required to recover after a system crash or power failure. 
  * There is nothing to troubleshoot.
* [Document Oriented](http://en.wikipedia.org/wiki/Document-oriented_database) 
* [JSON Based](http://en.wikipedia.org/wiki/JSON) - no XML, please
* Small resource footprint
* Simple Clean API for at least inserting and simple querying 
* Native Implementation (C/C++)
* Easy to Wrap for using in other languages (python, nodejs, ruby, java, c#, <put your favorite language here>)

## Related links

### BerkleyDB

* [BerkleyDB on Wiki](http://en.wikipedia.org/wiki/Berkeley_DB)
* [BerkleyDB on Architecture of Open Source Applications](http://aosabook.org/en/bdb.html)

### SQLite

* [The Architecture Of SQLite](http://www.sqlite.org/arch.html)
* [Categorical Index Of SQLite Documents](http://www.sqlite.org/docs.html)

### Other

* [UnQL: A Standardized Query Language for NoSQL Databases](http://www.dataversity.net/unql-a-standardized-query-language-for-nosql-databases/)
* [Is UnQL dead?](https://www.arangodb.org/2012/04/07/is_unql_dead) Attempt for similar DB which failed
