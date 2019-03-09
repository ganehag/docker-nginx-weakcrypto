# About this Repo

This repo contains Dockerfiles to build Nginx with *weak crypto*. So that HTTPS works on leagacy software like WinXP with IE8.

- Based on Debian stretch
- Support for Nginx stable and mainline
- Uses OpenSSL 1.0.2g as newer versions has removed the required ciphers.
