[![npm version](https://badge.fury.io/js/%40mapbox%2Fspritezero-cli.svg)](https://badge.fury.io/js/%40mapbox%2Fspritezero-cli)
[![build status](https://secure.travis-ci.org/mapbox/spritezero-cli.svg?branch=master)](http://travis-ci.org/mapbox/spritezero-cli)

# spritezero-cli

A command-line interface to [spritezero](https://github.com/mapbox/spritezero).

## Installation

    npm install -g @mapbox/spritezero-cli

## Usage

    spritezero [output filename] [input directory]

      --retina      shorthand for --ratio=2
      --ratio=[n]   pixel ratio
      --unique      map identical images to multiple names

Spritezero reads an input directory containing SVG files and generates a JSON
layout file and PNG spritesheet.

###UPD:
This version from https://github.com/dburnsii/spritezero-cli/tree/update-to-spritezero-7.0
