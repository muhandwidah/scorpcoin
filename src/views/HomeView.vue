<template>
  <div>
    <greetingComp id="greetingComp"/>
    <v-divider id="divider"></v-divider>
    <chartComp id="chartComp"/>
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
  import chartComp from '../components/chartComp.vue'

  export default Vue.extend({
    name: 'HomeView',

    components: {
      greetingComp,
      secondComp,
      thirdComp,
      chartComp,
    },
  })
</script>
<style scoped>
#chartComp{
  width: 100%;
}
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