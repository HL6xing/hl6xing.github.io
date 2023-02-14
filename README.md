6xing.top
开源主页，使用者请删除index.html里我的百度统计，如果你不删除直接就使用我的。你的点击访问ip不光看不到，还会全部出现在我的统计后台里。  
就有一个叼毛只改里面的内容文字图片，不看源码，又不删掉我的统计id.结果别人访问他的网站，我后台看的一清二楚。  
请删掉  
```<!--百度统计-->
		<script>
			var _hmt = _hmt || [];
			(function() {
			  var hm = document.createElement("script");
			  hm.src = "https://hm.baidu.com/hm.js?962b95c3**e*65***********"
			  var s = document.getElementsByTagName("script")[0]; 
			  s.parentNode.insertBefore(hm, s);
			})();
			</script>
```
  
  这一整段。
