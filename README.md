# eslint-plugin-myplugin



## Installation

You'll first need to install [ESLint](https://eslint.org/):

```sh
npm i eslint --save-dev
```

Next, install `eslint-plugin-myplugin`:

```sh
npm install eslint-plugin-myplugin --save-dev
```

## Usage

Add `myplugin` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
   "extends": [
        "plugin:myplugin/myConfig"
    ],
    "plugins": [
        "myplugin"
    ]
}
```

