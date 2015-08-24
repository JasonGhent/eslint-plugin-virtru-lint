# eslint-plugin-virtru-lint

foo

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-virtru-lint`:

```
$ npm install eslint-plugin-virtru-lint --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-virtru-lint` globally.

## Usage

Add `virtru-lint` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "virtru-lint"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "virtru-lint/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here





