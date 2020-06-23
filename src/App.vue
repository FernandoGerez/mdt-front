<template>
  <div id="app">
    <PublicNavbarComponent />
    <router-view/>
  </div>
</template>

 <script>
 import PublicNavbarComponent from '@/components/navbar/PublicNavbarComponent.vue'

 export default {
    components: {
      PublicNavbarComponent
    }
  }
 </script>