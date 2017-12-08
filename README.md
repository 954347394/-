<html>
<head>
<meta charset="utf-8">
<title>Baymax</title>
<style>
body {
    background: #595959;
}
#baymax 
{
  
/*设置为 居中*/
   margin: 0 auto;
 
   /*高度*/
  
  height: 600px;
 
   /*隐藏溢出*/   
 overflow: hidden;
}


#head {
   
 height: 64px;
  
  width: 100px;

  
  /*以百分比定义圆角的形状*/
 
   border-radius: 50%;

 
   /*背景*/
   
 background: #fff;

  
  margin: 0 auto;
   
 margin-bottom: -20px;

  
  /*设置下边框的样式*/
  
  border-bottom: 5px solid #e0e0e0;

  
  /*属性设置元素的堆叠顺序；
  
  拥有更高堆叠顺序的元素总是会处于堆叠顺序较低的元素的前面*/
  
  z-index: 100;

  
  /*生成相对定位的元素*/
  
  position: relative;
}

</style>





</head>


<body>
    
<div id="baymax">

      
  <!-- 定义头部，包括两个眼睛、嘴 -->
      
  <div id="head">
       
     <div id="eye"></div>
          
  <div id="eye2"></div>
          
  <div id="mouth"></div>
       
 </div>

     
   <!-- 定义躯干，包括心脏 -->
 
       <div id="torso">
            
<div id="heart"></div>
      
  </div>

     
  <!-- 定义肚子腹部，包括 cover（和躯干的连接处） -->
     
   <div id="belly">
    
       <div id="cover"></div>
       
 </div>     
  <!-- 定义左臂，包括一大一小两个手指 -->
       <div id="left-arm">       
   <div id="l-bigfinger"></div>       
    <div id="l-smallfinger"></div>     
  </div>      
 <!-- 定义右臂，同样包括一大一小两个手指 -->    
    <div id="right-arm">        
    <div id="r-bigfinger"></div>     
      <div id="r-smallfinger"></div>     
   </div>      
  <!-- 定义左腿 -->  
      <div id="left-leg"></div>
      
  <!-- 定义右腿 -->     
   <div id="right-leg"></div>
  
  </div>
</body
</html
