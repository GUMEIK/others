# jsdoc 的使用
## 安装
```npm install jsdoc --save-dev```
## 配置
在根目录下创建jsdoc.json文件
```json
{
    "source":{
        "include":["src/"]
    },
    "opts":{
        "encoding": "utf8",
        "destination": "./docs/",
        "recurse": true,
        "verbose": true
    }
}
```
## 使用
```jsdoc -c jsdoc.json```