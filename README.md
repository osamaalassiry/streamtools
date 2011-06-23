# StreamTools


## Introduction
This is a collection of scripts that deal with multimedia streams. 
They can be used to record, archive, convert and publish these streams.

## The Scripts

### streamdl
streamdl can be used to download a stream, either manually or by using crontab.
streamdl takes one parameter, the stream's name.

### streamrss
streamrss takes the media files downloaded by streamdl and automatically creates an RSS feed for them.

## Stream configurations
Stream configurations are plain textfiles stored in a subfolder of the location of the scripts, called streams.

### settings

#### streamdl
* time: defines how many seconds to record.
* streamurl: The URL of the stream.
* prefix: A prefix for the media files
* podpath: Where to store the media files
* daystokeep: How many days of media files to keep.
* format: The format to convert the media files to.

#### streamrss
* podurl: The web-accessible URL to the files.
* image: An image for the RSS feed.
* title: The title of the podcast
* link: A link to the website of the originator of the stream.

### Examples
Examples stream config is in the folder "streams".

