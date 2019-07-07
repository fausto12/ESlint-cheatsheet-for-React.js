# Cheatsheet: ESlint + Prettier extensions 

- code formatter for vs code --
custom rules/settings

```npm i prettier eslint-config-prettier eslint-plugin-prettier -D```

## To use with .eslintrc file

```
{
  "extends": [
    "react-app",
    "plugin:prettier/recommended"
  ],
  "rules": {}
}
```

## Editor settings

```

  "files.autoSave": "onFocusChange",
  "editor.formatOnSave": true,
  "eslint.autoFixOnSave": true,
  "eslint.alwaysShowStatus": true,
  "prettier.disableLanguages": ["js"],
  "editor.tabSize": 2,
  "[javascript]": {
    "editor.formatOnSave": false
  }
}
```


