```js
/**
 * 嘉诚前端  Frame
 */
var JCFF = {};

JCFF.getTop = function(){
    if(window.name === 'mainFrame'){
        return window.top;
    }
    return window;
}
```

**可以插入表格**

| 依赖插件名称 | 版本 |
| :--- | :--- |
| jquery | 1.10.2 |



