<template>
  <div class="containter">
  <Header/>
  </div>
  
</template>

<script>
  import Header from './components/Header.vue'



export default {
  name: 'App',
  components: {
      Header,
    
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.button1{
  display: inline-block;
  background: blue;
  color: #d14719;
  border: none;
  margin: 10px;
  font-size: 20px;
  font-family: times;
}

.button2{

}
</style>
