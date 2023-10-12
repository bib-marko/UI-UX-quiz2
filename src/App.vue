<template>
  <navBar/>
  <div class="main-body">
    <sideBar/>
    <div class="content-main">
      <contentMain/>
    </div>
    
  </div>
  
</template>

<script>
import NavBar from '@/components/NavBar'
import SideBar from '@/components/SideBar'
import ContentMain from '@/components/ContentMain'

export default {
  name: 'App',
  components: {
    NavBar,
    SideBar,
    ContentMain
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-size: 14px;
  color: #474b54;
  background: #f5f9fd;
}
.main-body {
  margin-left: 256px;
  margin-right: 280px;
}
.content-main {
  margin-left: 160px;
  margin-top: 20px;
}
</style>
