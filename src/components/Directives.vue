<template>
  <div>
    <span>{{ mess }}</span>
    <br />
    <button v-on:click="cap">To Capitalize</button>
    <br>
    <button v-on:click="small">To Small</button>
  </div>
</template>
<script>
export default {
  name: "Directives",
  data() {
    return {
      mess: "Ali",
    };
  },

  methods: {
    cap: function () {
      this.mess = this.mess.toUpperCase();
    },
    small: function () {
      this.mess = this.mess.toLowerCase();
    },
  },
};
</script>