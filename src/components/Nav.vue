<template>
  <div>
    <b>
      <span>{{ mes }}</span>
    </b>
  </div>
</template>
<script>
export default {
  name: "Nav",
  props: {
    mes: String,
  },
};
</script>