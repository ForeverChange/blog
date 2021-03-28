###  appendto（）

把内容添加到指定元素后面

`<html>
<head>
<script type="text/javascript" src="/jquery/jquery.js"></script>
<script type="text/javascript">
$(document).ready(function(){
  $("button").click(function(){
    $("<b> Hello World!</b>").appendTo("p");
  });
});
</script>
</head>
<body>

<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
<button>在每个 p 元素的结尾添加内容</button>
</body>
</html>`



上面的代码 在p元素后面添加 加粗的Hello World；



#### 		替换节点

**replaceWith（）**          使用新文本替换第一个P元素

```
$(document).ready(function(){
	$("button").click(function(){
		$("p:first").replaceWith("Hello world!");
	});
});
```



