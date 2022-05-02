<template>
  <dashboard/>
</template>

<script lang="ts">
import Vue from 'vue'
import Dashboard from './home/Dashboard.vue'

export default Vue.extend({
  components: { Dashboard },
  name: 'IndexPage'
})
</script>
