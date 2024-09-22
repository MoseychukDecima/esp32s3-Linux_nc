## Quick start

Install the following packages (Debian 12) before running the build scripts:

`autoconf automake bash bc bison build-essential cmake flex gawk git gperf help2man libncurses-dev libtool libtool-bin libusb-1.0-0 python3 python3-venv rsync texinfo unzip wget`

Run script `rebuild-esp32s3-linux-wifi-mpy-nc.sh`.

## About

Fork of jcmvbkbc/esp32-linux-build drawing upon forked versions of buildroot and esp-hosted.

Builds linux for ESP32-S3 N16R8 (16MB flash and 8MB PSRAM) including Micropython and NetCat (`nc`). Uses 16MB partion scheme.
