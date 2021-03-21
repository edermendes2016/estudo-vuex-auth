<template>
  <div id="app">
    
    <BarraNav />
    
    <router-view />
  </div>
</template>

<script>
import BarraNav from '@/components/BarraNav'

export default {
    components: {
      BarraNav
    }
}
</script>

