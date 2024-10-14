# upload-to-rbn
Based on the original for Red pitaya by Bjorn Ekelund SM7IUN, this is a small utility for uploading FT8 decodes from a QMTECH PDSDR designed by Pavel Demin (https://pavel-demin.github.io/qmtech-xc7z020-notes/) which is a multi-band FT8 receiver like the Red Pitaya, to the [Reverse Beacon Network](http://www.reversebeacon.net) via [RBN Aggregator](http://www.reversebeacon.net/pages/Aggregator+34). Call sign and grid are both set by RBN Aggregator.

Derivative work from [Pavel Demin](https://github.com/pavel-demin)'s `upload-to-pskreporter.c`.

Usage: 

`./upload-to-rbn broadcast-IP-address broadcast-UDP-port filename`
