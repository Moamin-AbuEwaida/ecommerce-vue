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

<style>
@import url("https://fonts.googleapis.com/css2?family=Nunito+Sans:wght@400;700;900&display=swap");
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Nunito Sans", sans-serif;
  text-decoration: none;
}
body {
  color: #121212;
}
</style>
