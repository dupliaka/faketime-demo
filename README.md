# This is an example of usage faketimelib

This application launches container with simulated time of 2.08.1990 00:00 
It shows current container time via java new Date() 

The  result is 

`Hello world! Today is:Thu Aug 02 00:00:00 GMT 1990`

### Requirements

- podman or docker*

### Quick start

To build an image

`podman build -t faketime-demo .`

To run the container

`podman run faketime-demo`

* On Fedora 31 and higher docker fails while downloading maven dependencies so use podman