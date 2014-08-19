//comment 不会run
programming language
作用：使网站能回应用户interactive，做app和游戏；评估信息例如使用最多的话题

，组织和呈现数据。

"What's your name?".length; 输出引号内的string数17，空格标点也算1个
confirm("I hate Chemistry!");弹出窗口确认
prompt("What's your name?");弹出窗口问你这个问题，回答后显示出来
5>4; 输出true 4>5; 输出false <=小于等于/>=/===等于/!==不等于

console.log(2 * 5) 输出括号中的运算结果10。运算有+ - * /，括号来控制运算顺

序,17%5即17除以5余数为2
console.log(2 * 5 > 6)输出true
console.log("Hello")输出引号内的文字Hello。注意：要输出文字必须加双引号

if ( ) {
    console.log( );
}没有分号
如果括号中为true，则run大括号中的内容，即输出。
else {
    console.log( );  
}没有分号
如果括号中为false，则run else后面大括号中的内容，即输出。

"wonderful day".substring(3,7)输出第4-7共4个字母。第一个字母w对应0，3是开始

截断的，7是终止截断的，即显示到6。

var myAge=23;定义变量myAge，变量Variable的值即等号后可以是""中的string，也

可以是数值
console.log(myAge);输出23
myAge=24;改变变量的值为24

var age = prompt("What's your age");设置用户回答问题的答案为变量


function
var divideByThree = function (number) {
    var val = number / 3;
    console.log(val);
};
divideByThree(7);定义divideByThree为function，首字母必须小写，几个单词的话

不能有空格，每个单词首字母大写。
输出7除以3的结果

var greeting = function (name) {
    console.log("Great to see you," + " " + name);+将双引号中的string和空格

和小括号中的string连接起来显示。大括号中的每行都要有分号
};
greeting("Emily");
输出Great to see you, Emily。改变"Emily"即name，是参数parameter，只能为一个

单词，重复大括号中的内容用function。

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

