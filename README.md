# libs-a20

This repo is used to backup libs cross-compiled on Allwinner A20.

## toolchain

* `sudo crossdev -S -t armv7a-hardfloat-linux-gnueabi`

## libs
* All libs are stripped already to decrease the size.
* json-c: 0.12
* openssl: 1.0.1j
* zlib: 1.2.8
* curl: 7.38.0 (no ssl support)
* libaacplus: 2.0.2
* x264: x264-snapshot-20141015-2245
* librtmp: git-a1900c3e152085406ecb87c1962c55ec9c6e4016
* ffmpeg: 2.4.2

## note for reference
* <https://gist.github.com/Akagi201/1f6fe5ff5b9b76c643af>