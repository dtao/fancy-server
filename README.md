Fancy Server
============

Runs a server that renders Markdown (*.md and *.markdown) files from the current directory, with a Bootstrap-styled layout.

## Installation

    npm install -g fancy-server

## Usage

Start a server for the current directory. Defaults to port 8000 and the default Bootstrap theme.

    fancy-server

Specify a custom port with `-p`:

    fancy-server -p 3000

Specify a [Bootswatch](http://bootswatch.com/) theme with `-t`:

    fancy-server -t readable

Specify a [highlight.js](http://highlightjs.org/) theme with `-h` (if your Markdown includes code examples):

    fancy-server -h rainbow

That's it!
