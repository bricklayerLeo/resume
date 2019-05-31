<template>


  <div class="bianbian clearfix" >
  <div class="haha">
   <div class="touxiang"></div>
   <div class="jieshao">
       <h3>刘维</h3>
       <h4>web 前端工程师</h4>
       <p>我是一个小胖子，没事就摸摸头</p>
   </div>
   <hr>
   <div class="xiangxi">
       <ul>
           <li><span class="iconfont">&#xe6fb;</span> 男 27岁 </li>
           <li> <span class="iconfont">&#xe637;</span>  深圳龙岗区</li>
           <li><span class="iconfont">&#xe60e;</span>  17328390822</li>
           <li><span class="iconfont">&#xe605;</span>  873634131@qq.com</li>
           <li ><span class="iconfont" >&#xe7a9;</span> https://github.com/msppyu1 </li>
       </ul>
   </div>
   <hr>
   <div class="github"></div>
   </div>
</div>
</template>

<script>
export default {
  name: 'bianbian'
}
</script>

 <style  scoped>
 .bianbian{
     height: 660px;
     background: white;
     margin-top: 10px;
  
    
 }
 

.touxiang{
    width: 100px;
    height: 100px;
    border-radius: 50%;
   margin: 0 auto;
    margin-top: 45px;
 background: url('../assets/yeye4.png')no-repeat left top/200%;
}
.jieshao{
    width: 200px;
    height: 100px;
    margin: 0 auto;
    text-align: center;
    line-height: 25px;

}

.xiangxi{
   margin: 0 auto;
 
   padding-left: 66px;
}
ul li{
    padding: 5px 0;
     font-size: 12px;
    
}


hr{
    width: 90%;
    margin: 0 auto;
}
ul{
    list-style: none;
}
ul span{
    top: 8px;
    position: relative;
    right:  20px;
    font-size: 25px;
}
</style>


