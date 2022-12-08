# React playground

## 开启局域网访问

```json
# vite.config
server: {
    host: '0.0.0.0'
},
```

## 配置别名

```json
# vite.config
resolve: {
    alias: {
        '@': path.resolve(__dirname, "src")
    }
}

# tsconfig.json
"paths":{
    "@/*": ["src/*"],
},
```

## 未设置 "baseUrl" 时，不允许使用非相对路径。是否忘记了前导 "./"

```json
# tsconfig.json
"baseUrl": ".",
```

## markdown preview

<!-- markdownlint-disable MD033 -->
<kbd>shift+command+v</kbd>

## markdown lint

[markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
