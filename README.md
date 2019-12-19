# Micropython C Generator

[![Build Status](https://travis-ci.org/wuhanstudio/Micropython-C-Generator.svg?branch=master)](https://travis-ci.org/wuhanstudio/Micropython-C-Generator)

A single-page site for generating C code for Micropython function implementation.

## Docker on the fly

    docker run -p 3000:8080 wuhanstudio/micropython-c-generator

## Build using Docker

    docker run -v `pwd`:/home node /bin/bash -c "cd /home && npm install && npm run build"

## Develop using Docker

    docker run -p 3000:8080 -v `pwd`:/home node /bin/bash -c "cd /home && npm install && npm run dev"

## Preview using Docker

    docker run -p 3000:8080 -v `pwd`:/home node /bin/bash -c "cd /home && npm install && npm run build && npm start"
