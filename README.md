# HA-Proxy-Config-Dockerfile
Dockerfile for HAProxy Load Balancer image + required config file

This repository contains the Dockerfile for a HAProxy Load Balancer
as well as the configuration file that is needed to properly build the image.

The configuration file is currently set up to expose at port 8000, and forwards requests to
3 containers named web1, web2, and web3 that are exposed at ports 8000 (the mod_wsgi default).

Server logs are currently set to send to the creator's papertrail account.
