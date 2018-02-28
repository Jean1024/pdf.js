### PDF.js 使用

1. 开启本地服务器

`browser-sync start --server --files "*.html"`

2. 地址后缀添加 `?[路径]`

例如 `http://localhost:3000/?1.pdf`

3. pdf地址修改文件地址 `viewer.js`

3650行
```javascript
    var DEFAULT_URL = window.location.href.split('?')[1];
```


