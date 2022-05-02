<template>
<div>
  <!-- <a-row>
    <a-col :span="8">col-12</a-col>
    <a-col :span="8">col-12</a-col>
    <a-col :span="4">col-4</a-col>
    <a-col :span="4">col-4</a-col>
  </a-row> -->
  <Banner />
  <!-- <base-input /> -->
</div>
</template>


<script setup lang="ts">
import Banner from '~/components/Banner.vue';
export default {
  components: { Banner },
  name: "Dashboard",
  
  data() {
    return {
      customers: "",
    };
  },
};
</script>

<style scoped></style>
