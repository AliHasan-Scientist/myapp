<template>
  <div>
    <p>{{ console }}</p>
  </div>
</template>
<script>
export default {
  name: "Users",
  data() {
    return {
      console: "Hello I a m child Of Home Component",
    };
  },
};
</script>