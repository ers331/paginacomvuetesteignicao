<template>
 <div class="menus">
  <menuTop />
  <menuVtc />
  <subnav />
  <menuLateral />
  <pagination />
 </div>
</template>



<script>
import menuTop from './menuTop.vue'
import menuVtc from './menuVtc.vue'
import subnav from './subnav.vue'
import menuLateral from './menuLateral.vue'
import pagination from './pagination.vue'
export default {
  name: 'menus',
  components: { menuTop, menuVtc, subnav, menuLateral, pagination}
}
</script>

