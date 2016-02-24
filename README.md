# Simple RSS Feed Reader

This is a simple reader to consume RSS feeds.

### Features

* Entering URL's of feeds you like.
* Main page displaying all feeds at once.
* Cache contents for offline reading.

### Data Modeling

Feeds | Entries
--- | ---
ID>> | ID
name | title
url | content
description | url
. | author
. | published
. | >>feed_id
