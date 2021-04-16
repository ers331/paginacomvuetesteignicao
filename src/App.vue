<template>
  <div id="app">
    <menus />
    <aticles />
  </div>
</template>

<script>
import Aticles from './components/aticles/aticles.vue'
import menus from './components/menus/menus.vue'
export default {
  name: 'App',
  components: {
    menus,
    Aticles, 
  }
}
</script>

