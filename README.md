# LAN File Transfer

Transfer files over LAN from your computer to a mobile device
![](https://github.com/vocolboy/lan-filetransfer/blob/master/demo.png)

Inspired by https://github.com/claudiodangelis/qr-filetransfer.

# Requirements
* PHP 5.6.0 or later 
* php_sockets extension  
(How to enable : https://stackoverflow.com/a/1361937 )

# Usage
Note: Both the computer and device must be on the same local area network.

`php transfer [filePath] [option]`

# Arguments
* `--port[=PORT]` The port to serve the application on. [default: 8080]
* `-h , --help` Display this help message
