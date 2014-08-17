HTML hypertext markup language
<!DOCTYPE html>写在开头，表示以下用的HTML，
<html></html>表示开始了
html分为<head> <title>显示的是新窗口上面的字
     和<body>
<>里的是标签tag，成对的，最后开的最先关。

超链接hyperlinks:<a href="http://www.baidu.com"> My favorite webpage</a>href是属性attribute

插入图片，将图片上传到网上，有个url，然后右键点击网页上的图片，copy url，
   <img src="url"/>无关标签</img>
   要想点击图片跳到另一个网页，就将<a>的内容写成图片
 
 <ol><li>元素 有序列表1.2.3.
 <ul>		  无序列表点

<p style属性="font-size:12px；
			  color: green;
			  font-family字体:Arial首字母要大写;
			  background-color背景颜色: red;
			  text-align文本位置:center居中/left/right
内容</p>
让文字粗体，在其前后加开关标签<strong></strong>
     斜体                 <em></em>

<table>
	<thead>
		<tr>
			<th colspan="2">该内容合并了该行的两列为一列，可作为表格的标题</th>
		</tr>

		<tr>
			<th>第一行第一列的标题，会居中，加粗</th>
			<th>第一行第二列的标题，会居中，加粗</th>
		</tr>
	</thead>
	<tbody>
		行row<tr>
			表格中的元素data<td>内容即第一列column<td>
			<td>内容即第二列</td>
		</tr>
	</tbody>
</table>

<div style="width:50px; height:50px; background-color:red">将页面分成若干部分division/区域blocks，便于分别style。例如这儿是显示一个红色的正方形
</div>

<span style="color:red">red</span>控制较小部分内容的style，例如这儿是让span这个标签里的内容变成红色

<!-- Make me into a comment.-->
tap相当于4个空格
