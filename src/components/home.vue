<template>
  <div class="w-90">
    <div class="img-wrapper" >
      <img src="../assets/my_img.jpg" class="rounded-circle img-fluid mx-auto d-block avatar" id="avatar"/>
    </div>
    <div class="text-bg px-5 pb-3 mx-auto">
      <h1 class="display-4 text-center text-light">
        Reymark Arsenio
      </h1>
      <p class="text-light text-center">
        I'm a front-end web developer focused in developing projects with efficieny and perfection.
      </p>
    </div>

  </div>
</template>

<script>
export default {
  data() {
    return {
      imgHeight:'100',
    }
  },
  mounted(){
    this.onResize();
    this.imgHeight = document.getElementById('avatar').offsetHeight;
  },
  methods:{
    onResize(){
      window.addEventListener("resize", function(){
        this.imgHeight = document.getElementById('avatar').offsetHeight;
      });
    }
  }
}
</script>

<style>
.img-wrapper{
  width:98%;
  height:100%;
  z-index: 3;
  position: relative;
}
.avatar {
  width: 30% !important;
  padding:10px;
  border:4px solid white;
  border-radius: 500px;
  -webkit-border-radius: 500px;
  -moz-border-radius: 500px;
  z-index: 2;
}

.text-bg {
  background-color: #212632;
  margin-top:-150px;
  padding-top: 170px;
  width:75%;
}

.text-bg p {
  font-size:23px;
}
</style>
