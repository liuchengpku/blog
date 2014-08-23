Objects
法1：literal notation
var me={
   key/property: value, 逗号，最后一个不用。
   name: 'Liu',
   age: 23，
   love:[], 也可以是数组
   Janet: {} 也可以是objects
}; 大括号表示是objects
var name1=me.name; 储存me中的信息或access properties用ObjectName.PropertyName或ObjectName["PropertyName"]

法2：constructor notation
var myObj = new Object();右边表示要定义个object，等于上面的var myObj={};
myObj["name"] = "Charlie";或
myObj.name = "Charlie";
若要添加一个object到数组中，成为其一个元素，则在上面三行之后
var myArray = [2,'love',myObj];
若console.log(myArray[2]); 输出 Object {name: "Charlie"} 

objects中套objects：
var friends = {}
friends.bill = {
   firstName: "Bill",
   lastName: "Gates",
   number: "(206) 555-5555"
}；
var list = function (friends) {
	
}

var o = { a: 1, b:2 };
for (var my in object) {
  
}
定义变量my，未赋值，即var my。找到前面定义的object即o中的所有key，按顺序，找到第一个，如a，赋值给my，即my='a'。此时，o[my]===o['a']===o.a===1


methods:
like a function associated with an object.
目的1：change object property values.例如：
var bob = new Object();
bob.name = "Bob Smith";
bob.age = 30;
bob.setAge = function (newAge){
  bob.age = newAge;
};
bob.setAge(40);
这里setAge是method，可以任意设置age
目的2：
bob.getYearOfBirth = function () {
  return 2014 - bob.age;
};
console.log(bob.getYearOfBirth());
()中可以无变量，就直接返回结果。
如果bob长大了一岁，bob.age = 31;则再次调用bob.getYearOfBirth 这个function时，console.log(bob.getYearOfBirth());会输出新的值；而如果不用function，这必须再次定义bob.getYearOfBirth=2014 - bob.age

2014.8.23 objects 1; Introduction;16 this 太难了 先学jquery
