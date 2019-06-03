<template>

  <div class="conent " >
    
  <p class="beijing">背景资料</p>
    
    <hr class="ojbk">
      
  <div class="miaohu">
         <div class="tubiao"><span class="iconfont">&#xe643;</span></div>
         <h3>自我描述</h3>
        <hr>
         <ul class="miaohu1">
         <li>个人主攻 Web 前端和 NodeJS 开发，3年+前端开发经验，参与或独立开发过多个核心项目，项目类型涉及：电子商务、教育服务、企业管理、SPA 应用（PC/Moblie）等等</li>
         <li>喜欢关注 Web 前端相关新技术（React、Angular、Vue...），对于新技术有很强的学习兴</li>
         <li>喜欢折腾造轮子，有一些简单的开源项目，不定时会更新 Github 小项目 5k+ Star</li>
         <li>热爱前端这份工作，也热爱一切美好的事物，对于我来说，是一种责任、是一种快乐</li>
         </ul>
    
   </div>
  

     <div class="miaohu">
        <div class="tubiao"><span class="iconfont">&#xe65c;</span></div>
         <h3>教育经历</h3>
         <hr>
         <div class="miaohu1">
           <p class="school"> <strong>东华理工大学，本科，</strong> 软件工程专业</p>
           <p class="timee">2012/09--2016/06</p>
         </div>
        
         
    
   </div>


  <div class="miaohu">
        <div class="tubiao"><span class="iconfont">&#xe604;</span></div>
         <h3>作品展示</h3>
         <hr>
         <div class="miaohu1">
         <zuopin />
        <zuopin />
          <zuopin />
        </div>
  </div>

 <div class="miaohu">
   <div class="tubiao"><span class="iconfont">&#xe614;</span></div>
         <h3>技能评价</h3>
        <hr>
         <div class="miaohu1">
         <tag :skill="this.skills"/>
         发，3年+前端开发经验，参与或独立开发过多个核心项目，项目类型涉及： 电子商务、教育服务、企业管理、SPA 应用（PC/Moblie）等等个人主攻 Web 前端和 NodeJS 开发，<br>3年+前端开发经验， 与或独立开发过多个核心项目，项目类型涉及： 电子商务、教育服务、企业管理、SPA 应用（PC/Moblie）等等
  </div>
  
  <div class="miaohu">
   <div class="tubiao"><span class="iconfont">&#xe624;</span></div>
         <h3>兴趣爱好</h3>
        <hr>
         <div class="miaohu1">
         <tag :aihao="this.aihao"/>
         发，3年+前端开发经验，参与或独立开发过多个核心项目，项目类型涉及： 电子商务、教育服务、企业管理、SPA 应用（PC/Moblie）等等个人主攻 Web 前端和 NodeJS 开发，<br>3年+前端开发经验， 与或独立开发过多个核心项目，项目类型涉及： 电子商务、教育服务、企业管理、SPA 应用（PC/Moblie）等等
</div>
  </div>
    
   </div>


</div>

</template>

<script>
import tag from '../subcomponents/tag'
import zuopin from '../subcomponents/zuopin'
export default {
  name: 'conent',
  data(){
    return{
      skills:["html5",
        "css3",
        "js",
        "vue.js",
        "jquery",
        "node.js",],
        aihao:[
        "电影","旅游","敲代码","吃饭","睡觉","回家",
        ]
        
      
    }
  },
  components:{
   tag,
   zuopin
  },
}
</script>

<style scoped>
.conent{
  background: white;
  
  font-size: 18px;
  height: 100%;
}
hr{
  width: 85%;
  margin-left: 90px;
  margin-top: 0;
  margin-bottom:0 ;
  
}
.ojbk{
  margin-left: 30px;
   width: 90%;
} 
.beijing{
  height: 50px;
  width:96% !important;
  line-height: 50px;
  margin:0 30px;
 

}
.miaohu h3{
  height: 50px;
  line-height: 50px;
  margin:0 90px;
  font-size: 18px;

  width:90%;
  padding-top: 8px;

}
.miaohu1{
  padding-top: 15px;
  padding-left: 125px;
  font-size: 14px;
}
ul{
  list-style-type:circle;
}
.tubiao{
  position: relative;
  top: 55px;
  left: 30px;
}
.timee{
  font-size: 12px;
  color: gray;
}
.miaohu{
  margin-top: -20px;
}
@media (max-width: 992px){
  .miaohu h3{margin:0 60px;}
  .miaohu1{
    padding-left: 60px;
  }
  .tubiao{
    left: 15px;
  }
 hr{
  width: 80%;
  margin:0 60px;
 
  
}
.ojbk{
 margin:0 10px;
   width: 90%;
} 
.beijing{
  margin-left: 15px;
}
}
</style>