<template>
  <div class="container-fluid home-content">
    <div class="row h-100">
      <div class="col-3 h-100 p-0 d-flex align-items-center ">

        <navbar></navbar>
      </div>
      <div class="col-9 my-auto">
        <home></home>
      </div>
      <div class="col-9 offset-3">
        <h1 style="height:800px;">hello</h1>
      </div>

    </div>
    <div class="bg-overflow mx-0 px-0"></div>

  </div>
</template>

<script>
import navbar from '../components/navbar.vue';
import home from '../components/home.vue';
export default {
  components:{
    'navbar':navbar,
    'home':home,
  },
   data () {
     return {

     }
   }
 }
</script>

<style>
.home-content{
  height:100vh;
  background-color: #262c3a;
}
.bg-overflow {
	width: 100%;
	height: 0;
	border-left: 25px solid transparent;
	border-right: 25px solid transparent;
	border-top: 50px solid #555;
}



</style>
<!--
<template>
  <div class="container-fluid home-content">
    <div class="row h-100">
      <div class="col-md-3 h-100 p-0 d-flex align-items-center ">
        <navbar></navbar>
      </div>
      <div class="col-md-9">


      </div>
    </div>

  </div>
</template>

<script>
import navbar from '../components/navbar.vue';
export default {
  components:{
    'navbar':navbar,
  },
   data () {
     return {

     }
   }
 }
</script>

<style>
.home-content{
  height:100vh;
  background-color: #262c3a;
}



</style> -->
