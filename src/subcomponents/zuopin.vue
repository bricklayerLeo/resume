<template>
    <div class="zuopin">
       <div class="qunaer">
           <div class="wenzi">个人主攻 Web 前端和 NodeJS 开发，3年+前端开发经验，参与或独立开发过多个核心项目，
               项目类型涉及：电子商务、教育服务、企业管理、SPA 应用（PC/Moblie）等等个人<br>主攻 Web 前端和 NodeJS
                开发，3年+前端开发经验，与或独立开发过多个核心项目，项目类型涉及：
             电子商务、教育服务、企业管理、SPA 应用（PC/Moblie）等等</div>
             <div class="picture">
            <div class="tupian"><img src="@/assets/mianshi1.png" alt=""></div>
            <div class="tupian"><img src="@/assets/mianshi1.png" alt=""></div>
            <div class="tupian"><img src="@/assets/mianshi1.png" alt=""></div>
            <div class="tupian"><img src="@/assets/mianshi1.png" alt=""></div>
            </div>
         </div>
         <div class="xiaochengxu"></div>
         <div class="boke"></div>
         <div class="heima"></div>
         <div class="xiaomi"></div>
         <div class="waimai"></div>
    </div>

   
</template>

<script>
export default {
    
}
</script>

<style scoped>

.picture{
    margin-top: 20px;

    display: flex;
    flex-direction: row;
    flex-wrap: wrap; 
}
.picture .tupian{
    width: 250px;
    height: 500px;
}


.tupian{
margin-right: 15px;
 cursor: pointer;
  transition: all 0.6s;
}
.tupian :hover{
    transform: scale(1.1)
}
@media (max-width: 992px){
    .wenzi{
    width:100%;
}
}
</style>

