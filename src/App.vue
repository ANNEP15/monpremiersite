<template>
<div> id="app>"
 <img alt="Vue logo" src=".assets/logo.png"/>
 <Bienvenu sur le site Annette/>
 
<messages/>
  </div>
  
</template>

<script>
<  messages from './components/messages.vue'>

export default {
  name: 'App',
  components: {
    messages
  }
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
</style>
