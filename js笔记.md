###js
+ 关于"a++"   "++a"的问题
		
		b=a++   ====>  b=a; a=a+1;
        b=++a   ====>  b=1+a

+ alert()  弹窗

+ console.log()  将信息输入到控制台

+ prompt()    让用户输入信息
 
+ var

 		var a=10;
            b=20;
  	        c=30;
            d=40;
	    console.log(a)   //10


+ 六大类型
   
 		     number      数
            string       字符串
			boolean      布尔
			null         空
			underfined   未定义
			object       对象

+ typeof(变量名)

			var num = 10;
            var str = "小黑";
            var fla = true;
         console.log(typeof num);  //num
         console.log(typeof str);  //string
         console,log(typeof fla);  //boolean


+ NaN  不是一个数字

###date  日期

          var date = new Date（）;
    年    var year = date.getFullYear（），
    月        month = date.getMonth(),
    日        day = date.getDate(),
    星期      week = date.getDay(),
    小时       hour= date.getHours(),
    分钟       minte = date.getMintes(),
    秒        second= date.getSeconds();

          var dateStr = year +"-"+ month +"-"+ day +" 星期"+ week +" "+ hour +":"+ minute +":"+ second; 
 
          console.log(dateStr)

### math
 
   天花板函数
   

    var a= Math.ceil(3.3)  //4 
                .floor(3.3) //3
                .max(3,6);   //6
                .min(3,6);  //3
                .min("ss" 6);  //nan
                .random();   


    var c = Math.round();

   




###比较运算符

 < >  <=  >=    ==   ===   !=  !==

+ 比较运算符得出的值为布尔值  true false
 






###逻辑运算符

+ && 并且    都真才真  有一个false就为false
+   true 遇到false返回,没遇到 就返回之后一个  值 (表达式的值)
+ || 或    有一个真就是真  遇到true就返回 没遇到 就返回之后一个  值 (表达式的值)   
+  
+ ! 非 
  


转换为boolean值为false的有 null 0 underfined  nan  ""   false  





###if语句

    If(条件句){
       条件为真的时候去做
    }else{
       条件为假的时候去做
          }



+ 练习

		var hig = prompt("请输入你的体重");
		
		var her = prompt("请输入你的身高");
		
		var bmi= hig/Math.pow(her,2);
		
		if(bmi>=32){
			alert("非常肥胖");
		}else if(bmi>=28){
			alert('肥胖');
		}else if(bmi>=25){
			alert("过重");
		}else if(bmi>=18.5){
			alert('正常');
		}else{
			alert('过轻');
		}


###三元表达式

   表达式 ? 如果表达式为true执行这个 : 如果表达式为false
   和if-else语句一样


+ if-else if......; 一般是对范围的判断,针对多个分之 
+ switch-case语句;一般是对具体的值的判断,多个分之


### 1+"str"==1str ,,,,, 1+2+3+"str"=6str ,,,, "str"+1+2+3 =str123      
### 1-"str"==nan
### 加俩端出现字符串就会是字符串样式,
### - /  % * 会把字符串变为数字



###for循环
    
+ 在写for循环的时候for( var i=0; i<100;i++);其中 var省略掉的话不    影响结果  

###break continue
+ break 跳出当前所在循环
+ continue  直接进入下一次循环

###数组
+  定义: 存储一组有序的数据,数据类型可以不一样
+  作用: 一次性存储多个数据
+  数组元素: 数组中存储的每个数据
+  数组的长度: 数组的元素的个数叫数组的长度
+  索引 :存储数组元素的编号,从0开始到数组的长度-1,索引是用来存储和读取数组的元素
+  冒泡排序: 求数组的和,最大值,最小值,平均值
+  var 数组名=[];空数组

###函数

+ 函数:把一些重复的代码封装起来,在需要的时候直接调用这个函数
+ 函数的作用: 代码的重用
+ 函数定义: 

         function函数名(){
                 函数体 
                 }

+ 函数调用: 函数名();

+ 参数:形参和实参
+ 形参:函数定义的时候函数名字后面的小括号内的变量, 
+ 实参:函数调用的时候小括号里的内容
+ 返回值: returen
+ 如果函数中有return,但后面没有内容这个函数没有明确返回值,如果函数调用了并且接受了结果为underfined





