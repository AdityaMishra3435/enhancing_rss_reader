Enhancing RSS Reader Project
==============

RSS-Reader is an open source, Web-based aggregator of content served by Web Feeds (RSS, Atom).

Pre-Existing Features
--------

- Supports RSS and Atom standards
- Organize your feeds into categories and keep track of your favorite articles
- Supports Web based and mobile user interfaces
- Keyboard shortcuts
- RESTful Web API
- Full text search
- OPML import / export
- Skinnable
- Android application

Additional Features Added:
--------
The following features were added using a Small Language Model:
1. Content summarization
2. Duplicate Detection
 

# Building RSS-Reader from source
------------------------------------

Prerequisites: JDK 8, Maven 3

Two versions of Java are needed to run this repository. RSS-Reader requires JDK 8 and Sonarqube requires Java 11. 

 
How to run
------------------------------------

RSS-Reader is packaged in several convenient formats. Installer can be found on the [Download Page](https://www.sismics.com/reader/#!/download).

For Docker usage, the following command can be used:

    docker-compose -p reader -f reader-distribution-docker/docker-compose.yml up
