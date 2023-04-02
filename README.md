# Q-POP-HTP

A linux scripting tool for generating high-throughput simulation jobs.

## TODO
1. migrate the documentation site from surge to GitHub pages and setup GitHub actions

## Publishing documentation site
```sh
yarn install
yarn run build
./node_modules/.bin/surge -p public/ --domain htp-studio.surge.sh
```
