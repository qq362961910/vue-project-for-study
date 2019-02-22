# vue-project-for-study

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## Project Init
1. 创建项目
    ``` bash
        vue create my-project
        or
        vue ui
    ``` 
2. 编辑package.json,配置rules
      ```yaml
      "eslintConfig": {
        "root": true,
        "env": {
          "node": true
        },
        "extends": [
          "plugin:vue/essential",
          "eslint:recommended"
        ],
        "rules": {
          "semi": ["error", "always"]
        },
        "parserOptions": {
          "parser": "babel-eslint"
        }
      }
      ``` 
3. 添加.eslintignore 
    ``` bash
    /build/
    /config/
    /dist/
    /test/unit/coverage/
    ```
4. 修复编码约定(fix source by lint)
    ```bash
    npm run lint
    ```







