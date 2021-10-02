<template>
  <div id="app">
    <VAC name="TestVAC" :data="viewProps" />
  </div>
</template>

<script>
import VAC from "./VAC.vue";

export default {
  components: { VAC },
  name: "app",
  data() {
    return {
      viewProps: {
        value: "value",
        list: [],
      },
    };
  },
};
</script>

<style></style>
