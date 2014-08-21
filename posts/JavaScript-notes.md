//comment 不会run
programming language
作用：使网站能回应用户interactive，做app和游戏；评估信息例如使用最多的话题，组织和呈现数据。

"What's your name?".length; 输出引号内的string的字符数17，空格标点也算1个

confirm("I hate Chemistry!");弹出窗口确认

prompt("What's your name?");弹出窗口问你这个问题，回答后显示出来
var color = prompt("What's your favorite primary color?","Type your favorite color here");在你回答的空格中显示后面一段话，将你的回答赋值给color这个变量。
prompt().toUpperCase()将你的回答输入的字符串中的所有字母都变成大写。
'HOW'.toLowerCase();全部变成小写字母how。

5>4; 输出true 4>5; 输出false <=小于等于/>=/===等于/!==不等于

console.log(2 * 5) 输出括号中的运算结果10。运算有+ - * /，括号来控制运算顺序,17%5即17除以5的余数，为2
console.log(2 * 5 > 6)输出true
console.log("Hello")输出引号内的文字Hello，里面的空格也会输出。注意：要输出文字必须加双引号或单引号，单引号和双引号唯一的区别就是单引号里面可以有双引号，双引号里面可以有单引号，例如var foo="It's elicious"，这时用单引号就会报错。

要测试你的JS代码是否正确，可以用谷歌浏览器右边工具，javascript控制台，在最下面输入，回车就会执行，不用输console.log就能输出结果。

if ( ) {
    console.log( );
}没有分号
如果括号中为true，则run大括号中的内容，即输出。
else {
    console.log( );  
}没有分号
如果括号中为false，则run else后面大括号中的内容，即输出。

"wonderful day".substring(3,7)输出第4-7共4个字母。第一个字母w对应0，3是开始截断的，7是终止截断的，即显示到6。
如果想输出其中一个字母，用后面学到的数组，例如：
var a="love";
a[1];即第2个字母o

var myAge=23;定义变量myAge，变量Variable的值即等号后可以是""中的string，也可以是数值
console.log(myAge);输出23
myAge=24;改变变量的值为24

var age = prompt("What's your age");设置用户回答问题的答案为变量


function
var divideByThree = function (number) {
    var val = number / 3;
    console.log(val);
};
divideByThree(7);定义divideByThree为function，首字母必须小写，几个单词的话不能有空格，每个单词首字母大写。
输出7除以3的结果

var greeting = function (name) {
    console.log("Great to see you," + " " + name);+将双引号中的string和空格和小括号中的string连接起来显示。大括号中的每行都要有分号
};
greeting("Emily");
输出Great to see you, Emily。改变"Emily"即name，是参数parameter，只能为一个单词，重复大括号中的内容用function。

var timesTwo = function(number) {
    return number * 2;
};
var newNumber = timesTwo(5);
console.log(newNumber);
输出10。只有用了return，则timesTwo(5)才是一个值，再将返回的函数值赋给新变量

function可以有多个参数function(length,width)  perimeterBox(2,3)

var computerChoice=Math.random();
console.log(computerChoice);
输出0-1之间的随机数
if(computerChoice < 0.33){
    computerChoice="rock";
}else if(computerChoice<0.67){
    computerChoice=  "paper";
}else{
    computerChoice= "scissors";
}
0.34-0.66之间输出paper
石头剪刀布.js文件


isNaN()如果括号中不是数字，例如'berry'，则为true；若为数字，则为false。


switch(变量){
	case '':  第一种可能性

	break;    不能忘记写了
	         第二种可能性
	default:  都不是以上的可能性

}

logical operators：
and (&&), or (||), and not (!).
例如 !(a || b) not a or b


