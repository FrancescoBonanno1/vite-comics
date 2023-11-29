<script>
import AppHeader from './components/AppHeader.vue'
import Appcontent from './components/Appcontent.vue'
import Appmerch from './components/Appmerch.vue'
import Appmain from './components/Appmain.vue'
import Appjumbo from './components/Appjumbo.vue'
import Appcomics from './components/Appcomics.vue'
export default {
  components: {
    AppHeader,
    Appjumbo,
    Appcomics,
    Appcontent,
    Appmerch,
    Appmain
  }
}
</script>

<template>
  <AppHeader />
  <Appjumbo />
  <Appcontent />
  <Appmerch />
  <Appmain />
</template>

<style scoped>
body {
  overflow-y: auto;
}
</style>
