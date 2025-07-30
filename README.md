# Use stockfish on the web

Short example how to use <https://github.com/lichess-org/stockfish-web> on a website.

- index.html has all the code and is pretty self explanatory
- server.js is a simple express server to serve the static files

## Install dependencies

Only express for the server, stockfish-web is already included in the index.html.

```bash
npm install
```

## NNUE Files

This repo includes the NNUE files for Stockfish 17.1.
If you want to use a different version, you will have to download the NNUE files yourself.

## Usage in your project

You will probably want to directly include the stockfish-web npm package in your project
and reference the .js file from there.

```
npm i @lichess-org/stockfish-web
```

Additionally you will need to include the NNUE files in your project.
Those can be obtained on <https://tests.stockfishchess.org/nns>.
After downloading the files you should place them in your projects static assets folder.
