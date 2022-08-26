<template>
  <div id="map">
    <template v-if="!!google && !!map">
      <slot />
    </template>
  </div>
</template>
<script lang="ts">
import { Loader } from '@googlemaps/js-api-loader'
import Vue from 'vue'
export default Vue.extend({
    
})
</script>