<style scoped>
h1 {
  font-weight: normal;
}
</style>

<template>
  <div>
    <h2>{{ name }}</h2>
  </div>
</template>

<script>
export default {
  name: "VAC",
  props: {
    name: String,
    data: Object | Array | Function | String | Number | Boolean | null,
    trace: String,
    listTrace: String,
    customEvent: Function,
    hidden: Boolean,
    maxWidth: Number | String,
    maxHeight: Number | String,
    useValue: String,
    useDefaultValue: String,
    useList: String,
    useEach: String,
  },
  created() {
    console.log(this.data);
  },
};
</script>
