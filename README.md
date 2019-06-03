Untrunc
=======

Restore a damaged (truncated) mp4, m4v, mov, 3gp video. Provided you have a similar not broken video. And some luck.


You need:

* Another video file which isn't broken
* Ubuntu Xenial 16.04
* Basic ability to use a command line


## Installing on Xenial

clone mdonahoe/untrunc
cd untrunc
./compile.sh


## Running
./untrunc <ok.mp4> <corrupted.mp4>

This will create corrupted.mp4_fixed.mp4


## Notes
Cloned from https://github.com/ponchio/untrunc with hacky support added for files >4GB.
