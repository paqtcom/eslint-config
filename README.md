# PAQT ESLint Config

These are paqtcom's default settings for ESLint and Prettier.

## Example

```json
{
    "extends": ["@paqtcom/eslint-config"],
    "rules": {
        "no-console": 2,
        "prettier/prettier": [
            "error",
            {
                "trailingComma": "es6",
                "singleQuote": true,
                "printWidth": 120,
                "tabWidth": 4
            }
        ]
    }
}
```

## Installation

```
yarn add @paqtcom/eslint-config babel-eslint eslint eslint-config-airbnb-base eslint-config-prettier eslint-plugin-html eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-prettier eslint-plugin-react eslint-plugin-react-hooks eslint-plugin-vue prettier --dev
```
