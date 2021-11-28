<template>
  <div class="flex flex-center">
    <h1>Notícias</h1>
  </div>
  <div class="flex flex-center">
    <q-btn color="green" text-color="black" label="Botão Novo" />
  </div>
  <div class="flex flex-center">
    <q-btn
      color="green"
      round
      size="sm"
      icon="eco"
    />
  </div>  
  <div class="flex flex-center">
    <q-btn round color="red" glossy icon="local_grocery_store" />
  </div>  

</template>

<script>
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'PageIndex'
})
</script>
