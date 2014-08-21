loop

for
for (var counter = 1; counter < 6; counter++) {
	console.log(counter);
}
输出
1
2
3
4
5
定义变量如counter，赋值1；循环运行的条件，false则停止；每次循环的条件：i++即i=i+1, i--, i+=3即i=i+3, i-=3,
he+=she是的he=he+she简写

Array
var arrayName = [data, data, data];每个data可以是数或string例如"red"
数组中的元素data的位置是固定的，从0开始。arrayName[2]是第3个元素。arrayName.length=3长度即元素的个数。
例如输出数组中的每个元素：
var cities = ["Melbourne", 64, true,false, "NYC"];
2D数组，例如var 2D=[[1,1],[2,4,6]];

for (var i = 0; i < cities.length; i++) {
    console.log("I would like to visit " + cities[i]);
}

var text = "Hey, how are you \ 
doing? My name is Emily.";
\避免一行太长

var a='love';
var i=123;
var hit=[];
hit.push(a);将a这个元素加入数组hit
hit[0];就会输出数组hit中的第一个元素
hit.push(i);再将i这个元素加入数组hit，会成为该数组的最后一个元素。
hit[1]+' '+hit[0];输出数组中的多个元素"123 love"

var text="tian qi bu hao Liu wo xianLg quit haoma Liu jique jiug Liu djif Liu jiu";
var myName="Liu";
var hits=[];
for (var i=0;i<text.length;i++){
    if (text[i]===myName[0]){
        for (var j=i;j<i+myName.length;j++){ 
            hits.push(text[j]);
        }
    }
}
在一个for循环里面的第二个for定义变量得用j=i，循环终止的条件！！！他想只要碰到名字的首字母L，就连续加入后面的两个字母iu，即把整个名字的单词都加入空数组。


while：使用前不知道循环多少次，比如随机数
while(当此条件为真，则运行大括号中内容){
	
}
当用数字在条件中时，jS认为1是true，0是false

var bool = true;
while(bool ){
    console.log("Less is more!");
    bool = false;
}
结果会输出Less is more!
true/false不加引号才是布尔值，否则是字符串了。但console.log("hello "+bool+"!")是输出hello true!

do{
	;
}while();
先运行do后面的内容，判断while后的条件，若为真，继续做do后的内容；若为假，这停止。

Math.floor()是小于等于括号中数的最大整数。例如5.9即5；-5.9即-6
例如var name=Math.floor(Math.random()*5 + 1) 使name是1、2、3、4、5中的一个。
