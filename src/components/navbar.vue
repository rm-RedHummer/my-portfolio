<template>

    <b-button-group class="nav-btn-group position-fixed">
      <b-button size="lg" class="text-left pr-5 pl-4">About me</b-button>
      <b-button size="lg" class="text-left pr-5 pl-4">Skills</b-button>
      <b-button size="lg" class="text-left pr-5 pl-4">Works</b-button>
      <b-button size="lg" class="text-left pr-5 pl-4">Contact me</b-button>
    </b-button-group>

</template>

<script>
export default {
}
</script>

<style>
.nav-btn-group{
  flex-direction: column;
  border-bottom: 5px solid #bb2129;
  margin-left: 6vw;
}

.btn-group > button {
  border-radius: 0;
  background-color: #212632;
  border:none;
}
</style>
