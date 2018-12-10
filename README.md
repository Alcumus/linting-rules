## Linting Rules

This repository contains common linting rules and other related rules/standards to be shared among multiple projects.

All changes to this project should be published under a new version number.

### Using This Project

With access to the private npm repository:

1. Install alcumus-common-tools.
2. Install linting or all default tools.

Without access to the private npm repository:

1. `npm i --save-dev alcumus-linting-rules`
2. `ln -s ./node_modules/alcumus-linting-rules/resources/.editorconfig .editorconfig`
3. Create a `.eslintrc.json` file (or similar for `tslint`/`stylelint`).
4. Add the following to the `.eslintrc.json` file:

```
{
    "extends": [
        "./node_modules/alcumus-linting-rules/resources/linting/eslint/default.js"
    ],
    "root": true
}
```
