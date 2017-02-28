# Motivation

Amazon S3 is not having a good day today, so I decided to write my own.

# Installation

1. Install [nginx](https://www.nginx.com/).
2. Put `index.json` somewhere, like `/var/www`.
3. Edit line 46 of `nginx.conf` to point to the location of `index.json` from 
   previous step, as well as making any changes needed for your server
   configuration.
4. Replace the default `nginx.conf` with this file.
5. Start nginx.

Congratulations! your server now works as well as
https://console.aws.amazon.com/s3/ at the time of this writing, 
2017-02-28T20:36Z.
