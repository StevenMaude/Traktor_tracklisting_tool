# Traktor tracklisting tool

## Rationale
It's not [just me](http://forum.djtechtools.com/showthread.php?t=60947) that finds [Traktor](http://www.native-instruments.com/en/traktor/)'s export playlist user interface [irritating](http://www.native-instruments.com/forum/showthread.php?162271-export-track-list-as-TEXT-file).

This will be a Python script to work around these issues.

## Possible approaches to look into
* Extract information from the .NML files.
* Scrape it from an exported HTML playlist.

Haven't decided on which yet, but I might provide tools for both.

## Possible features
* Create a new HTML playlist with a subset of the columns in the original.
* Extract information to text.
* [YouTube search](https://developers.google.com/youtube/v3/code_samples/python#search_by_keyword) for track to add link
