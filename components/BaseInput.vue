<template>
  <div>
    <a-row class="input-row">
      <a-col :span="7" :xs="22" :xl="7" :md="7"><a-input v-model="source"  size="large" placeholder="Source"/></a-col>
      <a-col :span="7" :xs="22" :xl="7" :md="7"><a-input v-model="Destination" size="large" placeholder="Destination"/></a-col>

      <a-col :span="7" :xs="22" :xl="7" :md="7">
        <a-date-picker show-time size="large" class="an-dp">
          <!-- <template #renderExtraFooter>extra footer</template> -->
        </a-date-picker>
      </a-col>
      <a-col :span="3" :xs="22" :xl="3" :md="3">
        <a-button type="primary" size="large">
          <!-- <template #icon><SearchOutlined /></template> -->
          Search
        </a-button>
      </a-col>
    </a-row>
  </div>
</template>
<script lang="ts">
export default {
  name: "BaseInput",
 
  data() {
    return {
      source: "",
      Destination: "",
    };
  },

  // mounted() {
  //     source:'kjfkivjfiv';
  //     Destination:'ndi'

  // },
};
</script>
<style scoped>
.components-input-demo-size .ant-input {
  width: 200px;
  margin: 0 8px 8px 0;
}
</style>
