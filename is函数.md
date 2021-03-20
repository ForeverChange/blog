 

trim()

作用:去除字符串两端空格

参数:需要去除空格的字符串

返回值:去除空格之后的字符串



```jQuery
var str ="   lyx   "
var res = $.trim(str)；
console.log("---"+res+"---")
```

$.isWindow

作用:判断传过来的对象是不是Window

返回:true/false



 $.inArray()

作用:判断传过来的对象是不是数组

返回:true/false



$.Isfunction()

作用:判断传过来的对象是不是函数

返回:true/false



holdReady()

作用:暂停入口函数 全部加载完成也不执行

```
holdReady(true)
//恢复
holdReady(false)
```

