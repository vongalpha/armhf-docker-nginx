# About this Repo

This is the Git repo of the official Docker image for [nginx](https://registry.hub.docker.com/_/nginx/), adjusted for hard-float ARM devices (ARMv7 and better). The corresponding image is available as [mazzolino/armhf-nginx](https://registry.hub.docker.com/u/mazzolino/armhf-nginx). See the
Hub page for the full readme on how to use the Docker image and for information
regarding contributing and issues.

## How to use the armhf version

Just replace the `nginx` image with `mazzolino/armhf-nginx` everywhere you use the image (ie. at `docker run`, `FROM nginx:..` etc).

## How to build the image yourself

This image is built from the [mazzolino/armhf-debian](https://registry.hub.docker.com/u/mazzolino/armhf-debian/) base image which contains emulation support. That means you can also build this image from your amd64 machine. (See the base image's page for more information.)
