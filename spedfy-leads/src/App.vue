<template>
  <div id="app">        
    <contact></contact>
  </div>
</template>

<script>
import Contact from './components/Contact'

export default {
  name: 'App',
  components: {
    Contact
  }
}
</script>

<style>
  body {
     background: lightblue url("./assets/background.jpg") no-repeat fixed center; 
  }  

  .jumbotron {
    background-color: #222222;
    margin-top: 45px;
    margin-right: 45px;
    margin-left: 45px;
  }

</style>
