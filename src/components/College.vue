<script>
import { ref } from "vue";
export default {
  name: "College",
  setup() {
    const Colleges = ref("信息工程学院");
    return { Colleges };
  },
};
</script>

<template>
  <div>
    <h1>{{ Colleges }}</h1>
  </div>
</template>

<style>
</style>