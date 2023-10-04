This repo is based directly on the official Arch package repo for jack2.

The difference is that it installs into /opt/jack2, and doesn't conflict with other JACK implementations.

Purpose is for running jackd in dummy mode on systems which have another Jack installed. To do so, run with LD_LIBRARY_PATH=/opt/jack2/lib.