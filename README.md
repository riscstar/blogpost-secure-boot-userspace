# This material accompanies the blog post: TODO

## Install dependencies:

Install mkosi: https://github.com/systemd/mkosi/tree/main?tab=readme-ov-file#installation

## Build an image:

    mkosi genkey # only needed to run once to generate the keys
    mkosi build

## Boot the VM:

    mkosi vm
