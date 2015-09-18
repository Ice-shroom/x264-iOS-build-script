# x264 iOS build script

**My blog: [http://depthlove.github.io/](http://depthlove.github.io/)**

This is a shell script to build x264 for iOS apps.

Tested with:

* x264-snapshot-20140914-2245
* Xcode 6.4

## Requirements

* https://github.com/libav/gas-preprocessor

## Usage

* To build everything:

        ./build-x264.sh

* To build for arm64:

        ./build-x264.sh arm64

* To build fat library for armv7 and x86_64 (64-bit simulator):

        ./build-x264.sh armv7 x86_64

* To build fat library from separately built thin libraries:

        ./build-x264.sh lipo
