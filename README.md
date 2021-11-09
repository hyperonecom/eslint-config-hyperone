# eslint-config-hyperone

eslint rules for hyperone

## how to use

install dependencies
```sh
npm install eslint --save-dev
npm install @hyperone/eslint-config --save-dev
```

add to your .eslintrc
```
extends: '@hyperone'
```

or use package.json
```json
  "eslintConfig": {
    "extends": [
      "@hyperone"
    ]
  },
  "scripts": {
    "lint": "eslint .",
    "fmt": "eslint . --fix"
  },
```
