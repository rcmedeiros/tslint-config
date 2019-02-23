## Install
```shell
npm install --save-dev tslint tslint-config-rcm
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
