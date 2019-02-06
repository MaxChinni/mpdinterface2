# mpdinterface2

**Version 2 is still under development**

You may encounter issues, so please have a look into the open tickets or file a new one. If you like to use a more stable version, you can grab v1 [here](https://github.com/sn0opy/MPD-Webinterface)

![Screenshot](http://i.imgur.com/3CuXNwE.png)

## Documentation

### Installation

1. Clone the repo under a web root, i.e.

    git clone https://github.com/MaxChinni/mpdinterface2 ~/public_html/mpdinterface2
2. Make those directory writable to the web server user, i.e.

    chown www-data ~/public_html/mpdinterface2
3. Visit the page via browser

### data/config.ini

#### main settings
- mpd_host
- mpd_port
- mpd_password (leave blank, is MPD is not password protected)

#### in-browser streaming settings
- mpd\_httpd\_host
- mpd\_httpd\_port
