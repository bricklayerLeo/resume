<template>


  <div class="bianbian clearfix" >

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
   <hr class="okk">
 
   <a href="https://github.com/msppyu1" class="github"><span class="iconfont">&#xe60a;</span></a>
   </div>

</template>

<script>
export default {
  name: 'bianbian'
}
</script>

<style scoped>
@keyframes toutou{
    
    30%{
        transform: translateX(20px) ;
        opacity: 1;
    }
    90%{
        transform: translateX(-20px);
        opacity: 1;
    }
    to{
        transform: none;
        opacity: 1;
    }
}
.bianbian{
    height: 660px;
    background: white;
    margin-top: 10px;
  
}

.touxiang{
    width: 100px;
    height: 100px;
    border-radius: 50%;
   
   position: absolute;
   left: 50%;
   margin-left: -50px;
    margin-top: 45px;
    background: url('../assets/yeye4.png')no-repeat left top/200%;
    opacity: 0;
}
.touxiang{
    animation: toutou 3s forwards;
}
.jieshao{
    position: absolute;
   left: 50%;
   margin-left: -100px;
    width: 200px;
    height: 100px;
    
    text-align: center;
    line-height: 25px;

}

.xiangxi{
   padding-left: 66px;
}
ul li{
    padding: 5px 0;
     font-size: 12px;
    
}
@media (max-width: 992px){
    
    .xiangxi{
        position: absolute;
        left: 50%;
        width: 250PX;
        margin-left: -125PX;
        
        }
        .okk{
         margin-top: 240px;
        }

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
.github{
   width: 100px;
   position: absolute;
   left: 50%;
   margin-left: -50px;
   text-align:center;
   padding-top: 40px;
   text-decoration: none;
}
.github span{
font-size: 45px;
}
</style>


