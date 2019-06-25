<template>
 <div class="body" style="">
  <div class="hello">
    
    {{msg}}
   
    
  </div>
  </div>
</template>

<script>
export default {
  name: 'App',
  data () {
    return {
      
      msg: '大傻逼'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.hello{
  border: 1px solid green;
  width: 60%;
  height: 400px;
  margin: 0 auto;
  background-color:#fff;
}
.body{
width:100%;height:500px;background-color:#ccc;
}
</style>
