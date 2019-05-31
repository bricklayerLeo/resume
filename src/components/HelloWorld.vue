<template>
  <div class="hello" >
    <div class="container-fluid" style="overflow:auto">
      
      <div class="row">
        <div class="col-md-3">
          <bianbian/>
        </div>
     
        <div class="col-md-9">
          <conent/>
        </div>
      </div>
    
    </div>
   </div>
</template>

<script>

import bianbian from '../subcomponents/bianbian'
import conent from '../subcomponents/conent'
import kuang from '../subcomponents/kuang'


export default {
  name: 'HelloWorld',
  data () {
    return{}
  },
  components:{
    bianbian,
    conent,
    kuang
  },

}
</script>


<style scoped>
.hello{
  background: #F0F0F0;
  height: 100%;
}

.col-md-3{
  padding-right: 0px;
  padding-left: 10px;
    position: fixed;
}
.col-md-9{
  padding-left: 10px;
  padding-right: 0px;
  margin-left: 25%;
}
@media (max-width: 992px){
  .col-md-3{
    position: static;
    /* width: 100%; */
  }
  .col-md-9{
    margin-left:0;
    /* width: 100%; */
  }
}
</style>
 


