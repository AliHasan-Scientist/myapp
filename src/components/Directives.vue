<template>
  <div>
    <span>{{ mess }}</span>
    <br />
    <button v-on:click="cap">To Capitalize</button>
    <br />
    <button v-on:click="small">To Small</button>
    <br />
    <table border="1px">
      <tr>
        <td>Name</td>
        <td>Email</td>
        <td>ID</td>
      </tr>
      <tr v-for="item in users" :key="item.id">
        <td>{{ item.name }}</td>
        <td>{{ item.email }}</td>
        <td>{{ item.id }}</td>
      </tr>
    </table>
  </div>
</template>
<script>
export default {
  name: "Directives",
  data() {
    return {
      mess: "Ali",
      users: [
        { name: "Ali", email: "test@gmial.com", id: 1 },
        { name: "Hussan", email: "test@gmial.com", id: 2 },
        { name: "Umer", email: "test@gmial.com", id: 3 },
      ],
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