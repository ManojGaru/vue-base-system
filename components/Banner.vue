<template>
  <div class="back-banner">
      <BaseInput/>
  </div>
</template>

<script lang="ts">
import BaseInput from "./BaseInput.vue";
export default {
  components: { BaseInput },
  name: "Banner",

//   data() {
//       return {
//           hiuhu:''
//       }
//   },
};
</script>
<style>
.back-banner {
  background-color: brown;
  height: 60vh;
  /* width: 100%; */
  justify-content: center;
  align-items: center;
  display: flex;
}

</style>
