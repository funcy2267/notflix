<h1 align="center">NOTFLIX</h1>
<p align="center">f@#k netflix use notflix a tool which search magnet links and stream it with peerflix</p>

> Watch this video to understand - [bugswriter's notflix (archived)](https://web.archive.org/web/20220128141100/https://www.youtube.com/watch?v=FbE19_omaWY)

### How does this work?

This is a shell script. It scape TPB and get the magnet link.
After this it use [peerflix](https://github.com/mafintosh/peerflix) to stream the video from magnet link.
For scraping script use simple gnu utils like sed, awk, paste, cut.

## Requirements

* [peerflix](https://github.com/mafintosh/peerflix) - A tool to stream torrent. `sudo npm install peerflix -g`

## Installation
Copy **notflix** to your **$PATH** and give execute permissions.
```sh
$ sudo cp notflix /usr/local/bin/notflix
$ sudo chmod +x /usr/local/bin/notflix
```
- To uninstall, simply remove `notflix` from your **$PATH**, for example `sudo rm -f /usr/local/bin/notflix`.

## License
This project is licensed under [GPL-3.0](https://raw.githubusercontent.com/Illumina/licenses/master/gpl-3.0.txt).
