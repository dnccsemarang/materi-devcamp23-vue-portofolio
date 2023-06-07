<script setup>
const props = defineProps({
  data: Array,
});
</script>

<template>
  <ul class="d-flex flex-wrap gap-2">
    <li v-for="data in props.data">{{ data }}</li>
  </ul>
</template>

<style scoped>
ul li {
  font-size: 15px;
  padding: 5px 20px;
  background-color: rgb(248, 248, 248);
  list-style: none;
  border-radius: 50px;
  font-weight: bold;
}
</style>
