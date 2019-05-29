# switz's eslint-config

## Motivation

I've had this lying around in my home dir `~/.eslintrc.js` for a while and decided to package it up so I can override it in project settings (e.g. targets) and include it in my projects for other contributors.

You probably have your own preferences, feel free to hack and slash it.

## Installation

```
# install eslint
$ yarn add -D @switz/eslint-config
# or
$ npm install -D @switz/eslint-config
```

Update your eslint config (`.eslintrc` or `.eslintrc.js`):

```
{
  "extends": [
    "@switz/eslint-config"
  ]
}
```

## Reference
https://eslint.org/docs/developer-guide/shareable-configs

## License
MIT, have fun

