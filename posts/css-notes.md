CSS
Cascading串联 Style Sheets 
用来描绘HTML的formatting 代替HTML中标签属性style=""的作用，
单独的CSS文件可以使所有相同标签中的内容一起设置为相同的style，简化代码；还可以设置不同HTML文件中的style
若把CSS语言放在HTML中，则放在<head>标签里的<style>标签中，
<head>
	<style>
		p{color:red;}
		span{}
	</style>
</head>
如何让一个HTML与CSS关联，在HTML中的<head>标签中的<title>标签前写
<link type="text/css" rel="stylesheet" href="CSS file address例如stylesheet.css"/>与img标签一样是Self-closing tags

selector {
    property: value;

}

color:#ffc125 hex value 16进制
font-size: px像素 1em手机常用的显示/2em是前者2倍大
font-family:serif/sans-serif/cursive默认的字体，首字母不必大写；例如Tahoma, Verdana, sans-serif;若系统没有第一种字体，则用第二种字体。
border边框:1px厚 solid实线 black
text-decoration:none链接无下划线，默认是有和蓝色，可以用a{}改变颜色

button
<div>

/*I'm a comment!*/

