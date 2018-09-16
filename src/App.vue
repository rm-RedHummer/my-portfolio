<template>
  <div id="app">
    <mainview></mainview>
    <skills></skills>
  </div>
</template>

<script>
import mainview from './views/mainview.vue';
import skills from './views/skills.vue';
export default {
  components: {
    'mainview':mainview,
    'skills':skills,
  }
}
</script>

<style>

</style>
