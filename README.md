Web Crawler Tool
================

Create a command line tool that crawls given website, reporting found pages and links found on each page.

Crawling should be limited to the pages on single domain, given `example.com` as starting point,
it should not fetch external links, e.g. on domains as `another.com`.

### Requirements

* Think how to balance speed of crawling and load on the crawled website, so that website does not get excessive amount of requests in a short period of time.
* Think if there is a way to avoid downloading links that will not contain links, like PDF documents or binary files.
* Use standard go library only.
* Push your code into GitHub repository, setting up appropriate GitHub actions.
* Use approaches and practices as you would do with any real production ready code.
