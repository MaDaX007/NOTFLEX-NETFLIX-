# NOTFLEX-NETFLIX-

<h1 align="center">NOTFLEX-NETFLIX-</h1>
<p align="center">BUMP netflix use notflex a tool which helps in searching magnet links and stream it with webtorrent</p>

##

### How does this work?

This is a shell script. It scrapes 1337x and gets the magnet link.
After this it uses [webtorrent](https://webtorrent.io/) to stream the video from the magnet link.
For scraping, the script uses simple gnu utils like sed, awk, paste, cut.

## Requirements

* [webtorrent](https://webtorrent.io/) - A tool to stream torrent. `npm install webtorrent-cli -g`

## Installation

### cURL
cURL **notflix** to your **$PATH** and give execute permissions.

```sh
$ sudo curl -sL "https://raw.githubusercontent.com/Bugswriter/notflix/master/notflix" -o /usr/local/bin/notflix
$ sudo chmod +x /usr/local/bin/notflix
```
- To update, just do `curl` again, no need to `chmod` anymore.
- To uninstall, simply remove `notflix` from your **$PATH**, for example `sudo rm -f /usr/local/bin/notflix.
