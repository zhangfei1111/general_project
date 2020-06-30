<template>
  <div class="home">
    <div class="header"></div>
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld
  }
};
</script>
<style lang="scss" scoped>
@import "../assets/css/them.scss";
.header {
  width: 100px;
  height: 100px;
  // 主题色
  background-color: $globalColor;
}
</style>
