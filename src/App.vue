

<template>
  <div id="app">
    <div class="container mt-3">
       <AppHeader /> 
      <router-view />
    </div>
  </div>
</template>

<script>
import AppHeader from "@/components/AppHeader.vue";
export default {
  components: {
    AppHeader,
  },
};
</script>



<style>
/* .page {
  max-width: 1000px;
  margin: auto;
} */
</style>