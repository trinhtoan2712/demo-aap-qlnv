<template>
  <TheHeader></TheHeader>
  <div class="frame">
    <TheSidebar></TheSidebar>
    <TheContent></TheContent>
  </div>
</template>

<script>
import TheHeader from './components/layout/TheHeader.vue'
import TheSidebar from './components/layout/TheSidebar.vue'
import TheContent from './components/layout/TheContent.vue'

export default {
  name: 'App',
  components: {
    TheHeader,TheSidebar,TheContent
  }
}
</script>

<style scoped>
@import url('./style/main/main.css')
</style>
