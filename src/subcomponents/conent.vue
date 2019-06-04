<template>

  <div class="conent " >
    
  <p class="beijing">背景资料</p>
    
    <hr class="ojbk">
      
  <div class="miaohu">
         <div class="tubiao"><span class="iconfont">&#xe643;</span></div>
         <h3>自我描述</h3>
        <hr>
         <ul class="miaohu1">
         <li>具有独立分析的能力，规范化的编程，标准化的代码编写习惯；有较强的事业心及责任感，能承受较大的工作压力；</li>
         <li>具有很好的执行力和团队合作意识，为人勤奋，吃苦耐劳；做事有耐心，也注重对旧知识的巩固。</li>
         <li>具有良好的沟通表达、团队协作能力，有较强的学习能力和探索精神，责任心强。</li>
         <li>热爱前端这份工作，也热爱一切美好的事物，对于我来说是一种快乐</li>
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
   <div class="tubiao"><span class="iconfont">&#xe614;</span></div>
         <h3>技能评价</h3>
        <hr>
         <div class="miaohu1">
         <tag :skill="this.skills"/>
         <ul class="miaohu11">
         <li>精通DIV+CSS布局的HTML代码编写，熟练手写符合W3C标准的代码，能够根据交互原型和UI设计图完整制作出网页；</li>
         <li>熟悉Javascript、css3和html5、ES6等技术，且能熟练运用JQuery框架实现网页常用特效，css3实现动画效果；</li>
         <li>熟悉Bootstrap，sass等前端框架，能够完成响应时设计以及流式布局的网页开发</li>
         <li>熟悉使用vue.js框架，vue-cli脚手架，webpack配置，项目打包，和Git操作</li>
         <li>熟悉使用Zepto、Swiper、iScroll、Touch、BootStrap等流行框架。</li>
    
         </ul>
  </div>

    <div class="miaohu">
   <div class="tubiao"><span class="iconfont">&#xe624;</span></div>
         <h3>兴趣爱好</h3>
        <hr>
         <div class="miaohu1">
         <tag :aihao="this.aihao"/>
         发，3年+前端开发经验，参与或独立开发过多个核心项目，项目类型涉及： 电子商务、教育服务、企业管理、SPA 应用（PC/Moblie）等等个人主攻 Web 前端和 NodeJS 开发
         ，<br>3年+前端开发经验， 与或独立开发过多个核心项目，项目类型涉及： 电子商务、教育服务、企业管理、SPA 应用（PC/Moblie）等等
</div>
  </div>

  <div class="miaohu zhanshi">
        <div class="tubiao"><span class="iconfont">&#xe604;</span></div>
         <h3>作品展示</h3>
         <hr>
         <div class="miaohu1">
         <zuopin />
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
.zhanshi{
  margin-bottom: 50px;
}
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
.miaohu11{
  padding-top: -15px;
  padding-left: -125px;
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
@media (max-width: 992px){
  .miaohu1{
    padding-right:20px;
  }
}
</style>