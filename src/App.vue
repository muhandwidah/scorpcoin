<template>
  <v-app id="mainApp">
    <navbar/>
      <v-main>
        <router-view/>
      </v-main>
    <bottomnav/>
  </v-app>
</template>

<script lang="ts">
import Vue from 'vue';
import navbar from './components/navbar.vue'
import bottomnav from './components/bottomnav.vue'

export default Vue.extend({
  name: 'App',

  data: () => ({
    //
  }),

  components: {
    navbar,
    bottomnav,
  }
});
</script>

<style scoped>

@font-face {
  font-family: Bank Sans EF CY;
  src: url('./assets/fonts/Bank Sans EF CY SemiCondensed Light.otf') format('opentype');
  font-weight: Light;
  font-style: SemiCondensed;
  font-family: Bank Sans EF CY, serif;
}
</style>