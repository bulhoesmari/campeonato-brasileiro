<template>
  <v-app>
    <AppTobBar/>
    <v-main>
      <MeuInicio/>  
    </v-main>
    </v-app>
</template>

<script>
import MeuInicio from './components/MeuInicio'
import AppTobBar from './components/shared/AppTobBar.vue'

export default {
  name: 'App',
  components: {
    MeuInicio,
    AppTobBar
  },
};
</script>

<style scoped>

</style>