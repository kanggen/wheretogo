<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <keep-alive>
      <router-view/>
    </keep-alive>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style scoped lang="stylus">
 

  #app {
    width: 100%;
    height: 100%;
    background :#f5f5f5;
  }
  body,html{
    width: 100%;
    height: 100%;
  }
</style>
