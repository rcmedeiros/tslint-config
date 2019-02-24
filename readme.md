# tslint-config

This is yet another tslint-config. It started as an overstrict set of rules which I relaxed over time. It's here just to keep code quality consistency.

## Install
```shell
npm i @rcmedeiros/tslint-config
```

## Usage
Make sure you have a TSLint plugin installed

In the project's root , create the file `tslint.json` and paste:
```json
{
    "extends": "tslint-config-rcm/tslint-config",
    "rules": {
        "no-addition": true
    }
}
```
