button
div{
	height:50px;
	width:120px;
	border-color:blue;
	background-color:red;
	border-radius:5px;使边框变圆
	margin:auto;使HTML元素居中
	text-align:center使文本居中
}

所有的HTML元素都能作为CSS的selector，包括body
只改变某个p标签的内容的样式，如果其位于三个div里面，则div div div h3{}
改变页面上的所有HTMKL元素*{}
A>B就是只对A下一级的B改变 如果是在A下一级的C里的B2就不变，而A B则B2也变 而且A与B只能相差一级 中间不能有C ABC均为标签
例如ul li p 不能ul>p 只能li>p 才是改变p，也可以用ul li p{}

<div class="square"></div> .square {}所有square的标签的内容一起改变
<div id="first"></div> #first {}指定特定标签的内容改变
<img src="" class="fancy"/>或<a href="http://" id="two不能用数字2">


Pseudo selectors
a:hover {}鼠标放到链接上后，链接的颜色字体等改变
a:active{}鼠标点击链接不松开时，链接的颜色字体等改变
a:link{}同a{}
a:visited{}在历史记录中的网页，为了标记已经访问过的网页

p:first-child {}上一级标签下的第一个标签改变
p:nth-child(3) {}上一级标签下的第3个标签p改变，如果上一级标签body下有h2,p,p,p，则是第2个p改变

a:nth-child(2){
    color:blue
}
a:hover{
    color:red
}
第二个链接会在鼠标放上后变红
但
a:hover{
    color:red
}
a:nth-child(2){
    color:blue
}
第二个链接不会在鼠标放上后变红。说明样式是会覆盖的。


display:block占满整个宽度full width 块集元素默认就是这样block elements default，如div就是
inline-block允许其他元素在它旁边，占同一行，每个元素都作为块集元素
inline使元素在同一行，宽度是它需要的，一般适用于块集元素。若作用于div则每个div都压扁成可能的最小宽度。
none不显示


box model
margin 外边距，元素与周围其他元素之间的空间，
	margin:auto使该元素左右两边的边缘相等，即在这一行居中，如将div的区域
	margin:1px 2px 3px 4px;top right bottom left
	margin-top:1px
border 边框，元素的边
	border:1px宽度 solid black
	border-width: 1px 2px 3px 4px;top right bottom left
	border-style:solid solid(border-right-style) solid none 默认值是none，则希望有边框出现，必须声明样式
	border-color:可以4边不同
padding 内边距，元素内容和边框之间的空间
	同margin
	padding:10px 4边都是10px
content 内容，例如p元素的内容就是其文本

背景是边框以内的，宽度和高度指内容的，内边距、边框和外边距都是可选的，默认值是零。

float:right 漂浮移到了最右边，不占空间。后面的元素会与之重叠/left
clear:left 立即移动到所有在页面左边漂浮的元素的下面/right/both
先写3div，设定高度和宽度和背景颜色；再第一个float:left，第二个float:right，第三个clear:both，显示成左右两块，下面一块；再分别填充文字图标内容。

position 若不设置，默认为static
position:relative 相对于其初始位置移动，则margin-left:20px相当于向右移动了20px，则新位置左外边距离原位置为20px
position:absolute 相对于已经定位即不是默认static的first parent 元素，若没有这样的元素，则定位相对于<html>
position:fixed 当鼠标上下滚动时，该元素在屏幕上不动。

