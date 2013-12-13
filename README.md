mep-diraudio
============

* Author: Clint Olson
* License: MIT
* Meaning: Use everywhere, keep copyright, it'd be swell if you'd link back here.

## Installation and Usage
_mep-diraudio: Stream MP3s with little overhead_

Uses MediaElement.js with the Playlist plugin, modifying Apache's directory listings to automatically stream all MP3 files listed.  In this way, you can put raw directories of MP3s on a server and stream them in a playlist-oriented fashion without having to specifically write a page for each folder.

### 1. Check the project out from github into the `/mep-diraudio` folder of your webserver.

`cd <path_to_webserver_root>; git clone https://github.com/coandco/mep-diraudio.git`

### 2. Copy `sample.htaccess` to `.htaccess` in the folder you wish to expose for MP3 streaming

Alternatively, if you have access to your website's Apache configuration, you can add the lines contained in sample.htaccess into that.

### 3. Enjoy!

The directory you enabled with the `.htaccess` should now have an HTML5 (or Flash/Silverlight, if you have an older browser) player that will allow you to play the music contained within.  Also, the "play" buttons next to each song should be clickable.

## Screenshot

![mep-diraudio in action](http://coandco.github.io/mep-diraudio/images/mep-diraudio_example.png "Basic example")
