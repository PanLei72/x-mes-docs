# X MES Documentation

This repository contains documentation for all [X MES](http://106.15.185.59:8881) . The documentation is published at http://106.15.185.59:8080.

## Building

* Install Node LTS release from https://nodejs.org

* Open terminal in `x-mes-docs` root folder and run:
  ```
  npm i
  npx antora antora-playbook.yml
  ```

* Open `jmix-docs/build/site/index.html` in a web browser.