<template>
  <div class="test">
    <h>hello 222222!!!</h>
    <Select></Select>
  </div>
</template>

<script>
  import Select from './subs/Select'
import SubCom from "./subs/SubCom";
export default {
  name: 'Test',
  components: {SubCom,Select},
  data(){
    return{
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<!--<style scoped>-->
<!--h{-->
  <!--font-weight: normal;-->
<!--}-->
<!--ul {-->
  <!--list-style-type: none;-->
  <!--padding: 0;-->
<!--}-->
<!--li {-->
  <!--display: inline-block;-->
  <!--margin: 0 10px;-->
<!--}-->
<!--a {-->
  <!--color: #42b983;-->
<!--}-->
<!--</style>-->
