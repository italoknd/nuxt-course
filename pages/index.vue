<template>
  <div>
    <div class="bg-gray-100">
      <div class="container mx-auto h-10 flex items-center mb-10 space-x-4">
        <nuxt-link to="/a-empresa">A empresa</nuxt-link>
        <nuxt-link to="/servicos">Serviços</nuxt-link>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage',
})
</script>
