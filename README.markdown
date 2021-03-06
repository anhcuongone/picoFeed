PicoFeed
========

PicoFeed was originally developed for [Miniflux](http://miniflux.net), a minimalist and open source news reader.

However, this library can be used inside any project.
PicoFeed is tested with a lot of different feeds and it's simple and easy to use.

[![Build Status](https://travis-ci.org/fguillot/picoFeed.svg?branch=master)](https://travis-ci.org/fguillot/picoFeed)

Features and requirements
-------------------------

- Simple and fast
- Feed parser for Atom 1.0 and RSS 0.91, 0.92, 1.0 and 2.0
- Feed writer for Atom 1.0 and RSS 2.0
- Import/Export OPML subscriptions
- Content filter: HTML cleanup, remove pixel trackers and Ads
- Multiple HTTP client adapters: cURL or Stream Context
- Proxy support
- Content grabber: download from the original website the full content
- Enclosure detection
- RTL languages support
- License: Unlicense <http://unlicense.org/>

Requirements
------------

- PHP >= 5.3
- libxml >= 2.7
- XML PHP extensions: DOM and SimpleXML
- cURL or Stream Context (`allow_url_fopen=On`)

Authors
-------

- Original author: [Frédéric Guillot](http://fredericguillot.com/)
- Contributors: See pull-requests, issues tracker and commit history

Documentation
-------------

- [Installation](docs/installation.markdown)
- [OPML file importation](docs/opml-import.markdown)
- [OPML file exportation](docs/opml-export.markdown)
- [Feed parsing](docs/feed-parsing.markdown)
- [Feed creation](docs/feed-creation.markdown)
- [Web scraping](docs/grabber.markdown)
- [Debugging](docs/debugging.markdown)
- [Configuration](docs/config.markdown)
