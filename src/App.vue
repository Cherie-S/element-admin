<template>
  <div id="app">
    <el-container>
      <el-header height="90px" class="header-top-menu">
        <e-header/>
      </el-header>
      <el-container>
        <el-aside width="200px">
          <nav-menu></nav-menu>
        </el-aside>
        <el-main>Main</el-main>
      </el-container>
    </el-container>
  </div>
</template>

<script>
  import NavMenu from '@/components/NavMenu'
  import Header from '@/components/Header'
  export default {
    name: 'App',
    components: {
      'nav-menu': NavMenu,
      'e-header': Header
    }
  }
</script>

<style>
/*#app {*/
  /*font-family: 'Avenir', Helvetica, Arial, sans-serif;*/
  /*-webkit-font-smoothing: antialiased;*/
  /*-moz-osx-font-smoothing: grayscale;*/
  /*text-align: center;*/
  /*color: #2c3e50;*/
/*}*/
/*.el-container {*/
  /*height: 600px;*/
/*}*/
.header-top-menu{
  background-color: #4d99e2;
  color: #fff;
  line-height: 90px;
}
</style>
