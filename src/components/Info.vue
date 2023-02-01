<template>
  <div>
    <ul>
      <li  v-for="item in items" :key="item.id">{{ item }}</li>
    </ul>
  </div>
</template>
<script>
export default {
  name: "Info",
  components: {},
  data() {
    return {
      items: ["JavaScript", "Java", "PHP"],
    };
  },
};
</script>
<style scoped>
ul {
    font-style: italic;
    font-size: 32px;
    text-align: left;
}
</style>