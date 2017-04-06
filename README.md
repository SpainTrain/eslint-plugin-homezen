# eslint-plugin-homezen

[![Greenkeeper badge](https://badges.greenkeeper.io/SpainTrain/eslint-plugin-homezen.svg)](https://greenkeeper.io/)

Presets and rules for HomeZen

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-homezen`:

```
$ npm install eslint-plugin-homezen --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-homezen` globally.

## Usage

Add `homezen` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "homezen"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "homezen/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here





