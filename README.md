# This material accompanies the blog post

accompanies the blog post: https://www.cnx-software.com/2025/08/15/embedded-device-security-protecting-linux-systems-with-modern-tools/

## Install dependencies:

Install mkosi: https://github.com/systemd/mkosi/tree/main?tab=readme-ov-file#installation

## Build an image:

    mkosi genkey # only needed to run once to generate the keys
    mkosi build

## Boot the VM:

    mkosi vm
