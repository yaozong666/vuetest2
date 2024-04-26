<script>
import { ref } from "vue";
export default {
  name: "Majors",
  setup() {
    const Majs = ref([
      { id: 1, name: "软件工程" },
      { id: 2, name: "网络工程" },
      { id: 3, name: "信息安全" },
      { id: 4, name: "物联网工程" },
      { id: 5, name: "物联网工程" },
      { id: 6, name: "智能科学与技术" },
      { id: 7, name: "空间信息与数字技术" },
    ]);
    return { Majs };
  },
};
</script>

<template>
  <ul>
    <li v-for="maj in Majs" :key="maj.id">{{ maj.name }}</li>
  </ul>
</template>

<style>
</style>