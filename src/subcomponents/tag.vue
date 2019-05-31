<template>
    <div class="tag " >
       <ul>
       <li v-for="item in skill" :key="item.index">{{item}}</li>
        </ul>
          <ul>
       <li v-for="item in aihao" :key="item.index">{{item}}</li>
        </ul>
    </div>
</template>

<script>
import { METHODS } from 'http';
export default {
    props:['skill','aihao'],
    methods:{
     
    }
   
}
</script>

<style scoped>
ul li{
    width: 60px;
    height: 25px;
    border-radius: 5px;
    background: #5BC0DE;
    color: white;
    text-align: center;
    line-height: 25px;
    margin-right: 10px;

}
ul{
    display: flex;
    flex-direction: row;
    list-style: none;
}

</style>


