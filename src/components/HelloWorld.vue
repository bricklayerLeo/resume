<template>
  <div class="hello" >
    <div class="container-fluid">
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


<style scss scoped>

.container-fluid{
 
  height: 100%;
}
.row{
  background:#F3F3F3;
  height: 100%;


}

.col-md-3{
  margin-top: 10px;
     padding-left: 0;
     padding-right: 10px;
      margin-left: 10px;
    position: fixed;
}
.col-md-9{
  margin-top: 10px;
  padding-left: 10px;
  padding-right: 10px;
  margin-left: 25%;
overflow: hidden;

}
@media (max-width: 992px){
  .col-md-3{
    position: static;
   margin: 0  -10px;
   margin-bottom: 10px;
  }
  .col-md-9{
    margin-left:0;
    margin: 0 -10px;
  }
}
</style>