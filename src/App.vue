<script setup>
import { RouterLink, RouterView } from 'vue-router'
import SideMenu from './views/SideMenu.vue'
</script>

<template>
 <div class="container-fluid"
 style="margin-top: -70px" 
 >
  <div class="row">
    <div class="col-3">
    <SideMenu/>
  </div>
  <div class="col-9">
    <RouterView />
  </div>
  </div>
 </div>
</template>
<style>
body{
  background-color: #000000;
  padding: 0;
  margin: 0;
}
.box{
  background-color: #121212;
  border-radius: 8px;
}
.col-9{
  padding: 0px !important;
}
</style>

