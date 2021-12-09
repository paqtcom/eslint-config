# Way2Web ESLint Config
These are Way2Web's default settings for ESLint and Prettier.

## Example
```json
{
  "extends": [
    "@way2web/eslint-config"
  ],
  "rules": {
    "no-console": 2,
    "prettier/prettier": [
      "error",
      {
        "trailingComma": "es5",
        "singleQuote": true,
        "printWidth": 120,
        "tabWidth": 8,
      }
    ]
  }
}
```

## Installation
```
yarn add @way2web/eslint-config babel-eslint eslint eslint-config-airbnb-base eslint-config-prettier eslint-plugin-html eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-prettier eslint-plugin-react eslint-plugin-react-hooks eslint-plugin-vue prettier --dev
```
