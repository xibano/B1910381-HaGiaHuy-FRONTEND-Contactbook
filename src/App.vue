<script>
import AppHeader from "@/components/AppHeader.vue";

export default {
  components: {AppHeader,},
};
</script>

<template>
  <div id="app">
    <App-Header />

    <div class="container mt-3">
      <router-view />
    </div>
  </div>
</template>