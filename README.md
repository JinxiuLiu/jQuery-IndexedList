# jquery-indexedlist.js
移动端索引列表，根据mui-indexedlist更改而来，现在基于jquery，不用引入mui的js、css文件。

## Demo
see the https://jinxiuliu.github.io/jQuery-IndexedList/example/[https://jinxiuliu.github.io/jQuery-IndexedList/example/]

## Install
```
<link href="mui.indexedlist.css" rel="stylesheet" />
...
<script src="jquery.indexedlist.js" type="text/javascript"></script>
```

## Usage
```
$(function() {
    $('#list').IndexedList({
        $bar: $('.mui-indexed-list-bar'),   // 存储索引的盒子
        $inner: $('.mui-indexed-list-inner'),   // 列表盒子
        $alert: $('.mui-indexed-list-alert')    // 显示索引提示的盒子
    });
});
```
Tip： 索引`data-group`不可更改，如有需要请直接更换js文件中的源码。
具体详情请查看示例。

## License
MIT

