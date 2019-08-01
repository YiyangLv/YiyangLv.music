<template>
  <div id="app">
    <Mheader></Mheader>
    <tab></tab>
    <keep-alive>
    <router-view></router-view>
  </keep-alive>
  </div>
</template>

<script>
import Tab from './components/tab/tab'
import Mheader from './components/m-header/m-header'
export default {
  components:{
    Tab,
    Mheader
  }
}
</script>
<style >

</style>
