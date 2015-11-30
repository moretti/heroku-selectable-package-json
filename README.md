heroku-selectable-package-json
==========================

## Usage

It's very simple. This buildpack just moves the package.json located at `$PACKAGE_JSON_PATH` to `./package.json`.

```
$ heroku config:add PACKAGE_JSON_PATH=modules/server/package.json

$ cat .buildpacks
https://github.com/moretti/heroku-selectable-package-json.git
https://github.com/heroku/heroku-buildpack-nodejs
```
