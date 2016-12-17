# Test Scripts

Collection of small scripts designed to work with TapDance.

This is basically a dump and I don't guarantee your computer won't catch
on fire, if you try to use that.

 * twitter_wget.sh - simply wget's twitter

 * go-1.7.4_wget.sh - downloads Golang 1.7.4 acrhive (~81MB)

 * ip.sh - queries http://ipinfo.io with curl for current ip

 * nc_send.sh - sends random data to poor innocent server
   (specify how much data, e.g. 21k or 42m)

 * seq.py - sends and receives enumerated bytes of data and checks if they are
   received successfully and in order. Blatantly stolen from
   [ewust's repo](https://github.com/ewust/sendseq).
   To use, point TapDance server into seq.py reciver
   and proxy seq.py sender through TapDance client.
