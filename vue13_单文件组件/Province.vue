<!-- 引入子组件-->
import City from './City.vue'


 <!--组件结构_模板view-->
<template>
  <div>
      {{name}} 
      <City></City> 
  </div>
</template>


<!-- 组件交互相关代码(数据、方法等) -->
<script>
export default {
  name :"Province",
  data(){
        return {
            name : "安徽省"
        }
      },
      components:{
          City //子组件
      }
}
</script>

