<template>
  <FrontNavBar />
  <router-view />
</template>

<script>
import FrontNavBar from '@/components/FrontNavbar.vue'

export default {
  components: {
    FrontNavBar
  }
}
</script>
