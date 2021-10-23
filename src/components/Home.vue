<template>
  <div>
    <h1>This is Home Component</h1>
    <Users />
  </div>
</template>
<script>
import Users from "./Users.vue";
export default {
  name: "Home",
  components: {
    Users,
  },
};
</script>
<style scoped>
h1 {
  background-color: rgb(213, 255, 149);
  color: black;
  font-family: "Courier New", Courier, monospace;
}
</style>