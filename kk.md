# markdown格式
## 二级标题
### 三级标题
   - 列表1
   - 列表2
   - 列表3

     *斜体*
     **粗体**
    --- 横线
     ~~删除线~~
     ` code`
     > 引用
     
     [链接](http://www.baidu.com)
     ![图片](http://www.baidu.com/img/baidu_jgylogo3.gif)
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
