<template>
  <div>
    <greetingComp id="greetingComp"/>
    <v-divider id="divider"></v-divider>
    <secondComp/>
    <v-divider id="divider"></v-divider>
    <thirdComp/>
    <v-divider id="divider"></v-divider>
  </div>
</template>

<script lang="ts">
  import Vue from 'vue'
  import greetingComp from '../components/greetingComp.vue'
  import secondComp from '../components/secondComp.vue'
  import thirdComp from '../components/thirdComp.vue'

  export default Vue.extend({
    name: 'HomeView',

    components: {
      greetingComp,
      secondComp,
      thirdComp,
    },
  })
</script>
<style scoped>
#greetingComp{
  margin-top: 5%;
}
#divider{
  margin-top: 5%;
  margin-bottom: 5%;
  width: 85%;
  margin-left: auto;
  margin-right: auto;
}
</style>