# docker-roots

## Purpose

This image was created specifically for usage with continuous integration systems, and contains the minimum requirements to deploy websites with [netlify](https://www.netlify.com). 

## Details

### Base Image

* [node (boron)](https://hub.docker.com/r/library/node/) - The latest Node LTS (Boron) image

### Additional Node Modules

* [Netlify](https://github.com/netlify/netlify-cli) - Netlify CLI.

## Colophon

Inspired by [docker-firebase](https://github.com/devillexio/docker-firebase).
