
- xulie 1
- xulie 2
- ---
- xulie3    
  xulie4


  # MARK DOMN 
   ## example
   ### sdada
     ** 粗体**

     *斜体*

     ~~删除线~~
     
     ` code`
` const q1 = new Promise((resolve,reject)=>{
    //    resolve("成功1数据");
       reject("失败1信息");
   });

   q1.then(res=>{
       console.log(res);
       return new Promise((resolve,reject)=>{
        resolve("成功2数据");
       })

   },err=>{console.log("1失败")
    throw new Error("err");//抛出错误 直接走到下一个then的catch
   })
   //返回上一个then的返回值在catch之前
   .then(res=>{
       console.log(res);
   },err=>{console.log("任务2失败")})
   
 `
     > 引用
     1. 列表
  1. 列表


[] [ dasdasd]
[dasdasd]: https://www.baidu.com

.sdas
.asdasdas
.asdasdasd
.asddasdwqedewadsa
