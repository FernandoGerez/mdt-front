<template>
  <div id="app">
    <PublicNavbarComponent />
    <router-view/>
    <PublicFooterComponent />
  </div>
</template>

 <script>
 import PublicNavbarComponent from '@/components/navbar/PublicNavbarComponent.vue'
 import PublicFooterComponent from '@/components/site/PublicFooterComponent.vue' 
 export default {
    components: {
      PublicNavbarComponent,
      PublicFooterComponent
    }
  }
 </script>