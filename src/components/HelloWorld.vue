<template>
  <div class="hello">
    <h1 title>{{msg}}</h1>
    <h2 subtitle>{{msg2}}</h2>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
    msg2: String    
  }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

  @import url('https://fonts.googleapis.com/css2?family=Merriweather:ital,wght@1,400;1,900&display=swap');

  h1{
    margin-top: 180px;
    text-align: center;
    color: #c8102e;
    text-transform: uppercase;
    letter-spacing: 1px;
    font-family: 'Merriweather', serif;
    font-weight: 400;
    font-size: 80px;
    text-shadow: 2px 2px  #c8102e;
  }
 
h2{
  margin-top: -150px;
    text-align: center;
    color: #0099ff;
    text-transform: uppercase;
    letter-spacing: 1px;
    font-family: 'Merriweather', serif;
    font-weight: 300;
    font-size: 60px;
    text-shadow: 2px 2px  #0099ff
;
}
</style>
