<template>
<div>
    <header class="public-header">
      
      <div class="container">
          <div class="row">
              <div class="col text-center">
                  <button>
                      Busco un profesional
                  </button>
                  <button>
                      Soy un profesional
                  </button>
              </div>
          </div>
      </div>

      <b-container class="mt-5">
          <b-row class="justify-content-md-center">
              <b-col cols="6" class="text-right">
                  <b-form-input type="search" placeholder="Buscador" class="text-uppercase" />
              </b-col>
          </b-row>
          <b-row class="justify-content-md-center mt-5">
              <b-col cols="6" class="text-center">
                  <h5 class="text-uppercase">mar de trabajo</h5>
                  <p class="mt-2">
                      Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dolorem, illo. Odio voluptas ipsa harum possimus unde deserunt quisquam iste magnam! Hic similique omnis, iusto qui accusamus voluptates officia adipisci ipsa.
                  </p>
              </b-col>
          </b-row>
      </b-container>
  </header>
  <PublicGridItemComponent />
  <PublicSloganComponent />
</div>
  
  

</template>

<script>
import PublicGridItemComponent from '@/components/Items/PublicGridItemComponent.vue'
import PublicSloganComponent from '@/components/site/PublicSloganComponent.vue'
export default {
    name: 'PublicHomeComponent',
    components: {
        PublicGridItemComponent,
        PublicSloganComponent
    }

}
</script>