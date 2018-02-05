<template>
  <div id="app" class="container">
    <app-header />
    <div class="row">
      <div class="col-md-12">
        <router-view/>
      </div>
    </div>
  </div>
</template>

<script>
  import Header from './components/Header'
  export default {
    components: {
      appHeader: Header
    }
  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
