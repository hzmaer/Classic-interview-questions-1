# Classic-interview-questions-1
javascript
一.(1)var a = {name: 1};

   var b = a;
   
   console.log(a);
   
   console.log(b);

   b.name = 2;
   
  console.log(a);
  
  console.log(b);

  var b = {name: 3};
  
  console.log(a);
  
  console.log(b);

  运行 test.js 结果为：

  { name: 1 }
  
  { name: 1 }
  
  { name: 2 }
  
  { name: 2 }
  
  { name: 2 }
  
  { name: 3 }
  
  (2)
  
