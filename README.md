# docker-ubisecure
This repository contains script and dockerfiles to dockerize Ubisecure SSO and CustomerID applications.

Design principles on these have been:
* Use as much existing official docker images as possible.
* Minimize amount of Ubisecure customizations as much as possible.
* Only one role per containers.
* Make containers as generic as possible.
* TODO: High availability configuration is used for everything
* TODO: Security by default...

I hope that some day Ubisecure will include these scripts to part of their build process and start provide pre-created docker images for their customers.

# Usage
Download https://demo.ubisecure.com/extranet/downloads/SSO/8.2/sso-8.2.19-unix.tar.gz to ubisecure-sso folder
and https://demo.ubisecure.com/extranet/downloads/CustomerID/5.x/5.2/5.2.7/customerid-5.2.7-linux.tar.gz to both ubisecure-sso and ubisecure-cid folders.

Follow readme files on folders