# Classic-interview-questions-1
javascript
一.复制引用类型变量值与复制基本类型变量值

(1)

   var a = {name: 1};

   var b = a;
   
   console.log(a);
   
   console.log(b);

   b.name = 2;
   
  console.log(a);
  
  console.log(b);

  var b = {name: 3};
  
  console.log(a);
  
  console.log(b);

  运行结果为：

  { name: 1 }
  
  { name: 1 }
  
  { name: 2 }
  
  { name: 2 }
  
  { name: 2 }
  
  { name: 3 }
  
  (2)
  
  var a=1;
  
  var b=a;
  
  var a=2;
  
  console.debug(a);//2
  
  console.debug(b);//1
  
  
  
