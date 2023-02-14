<template>
  <div>
    <HeaderPart />
    <router-view />
  </div>
</template>

<script>
import HeaderPart from "@/components/HeaderPart.vue";

export default {
  components: {
    HeaderPart,
  },
};
</script>

<style></style>
