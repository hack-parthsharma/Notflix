<h1 align="center">NOTFLIX</h1>
<p align="center">Fuck netflix use notflix a tool which search magnet links and stream it with peerflix</p>

##
<p align="center">
<img src="./preview.gif" alt="Video Preview" width="500px">
</p>


### How does this work?

This is a shell script. It scrape 1337x and get the magnet link.
After this it use [peerflix](https://github.com/mafintosh/peerflix) to stream the video from magnet link.
For scraping script use simple gnu utils like sed, awk, paste, cut.

## Requirements

A tool to stream torrent. `sudo npm install peerflix -g`

## Installation

cURL **notflix** to your **$PATH** and give execute permissions.

- To update, just do `curl` again, no need to `chmod` anymore.
- To uninstall, simply remove `notflix` from your **$PATH**, for example `sudo rm -f /usr/local/bin/notflix.


