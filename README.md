S3 Connector
====================================

S3 Connector gives you easy to user interface and upload your on-premise large data files to S3 Buckets.

Requirements
------------
Modern Browser
Latest Firefox, Chromium, Opera, IE (>= 10)
PHP server
Composer to download aws-php-sdk (http://docs.aws.amazon.com/aws-sdk-php/guide/latest/installation.html)

Installation
-------------
Rename the config.php.dist to config.php and set the constants
accordingly. You also need to run the `composer install` command to
download the aws-php-sdk. Then just open the `upload.html` or
`raw_upload.html` on browser to see the demonstrations (as a server
file, not local file).

Files
-----

* server.php - The server file, it does the creation, completion of
multipart upload. And also it signs the requests to make the browser to
upload the file parts.

* raw_upload.html - This file is the demo of how to connect to the
server, uses jquery (and firebug lite for easy debug viewing), and I am not so
good with javascript, so forgive me for this type of coding :-(

* upload.js - An attempt to make an object out of the javascript part,
the smallest documentation is present in the file

* upload.html - Demonstration of upload.js, if you are too lazy, you can
use this as your starting point.

* Libraries - they are helpers. jquery, firebug_lite, etc. You should
respect their licenses.

License
-------
Actually you can think of this code on public domain :P
Just a mention or gratitude of this work is enough :)
(not needed at all though)

Contributors
------------
@thecolorblue - Brad Davis - https://github.com/thecolorblue

@ienzam - Md. Enzam Hossain - https://github.com/ienzam
