<template>
  <h1>{{ msg }}</h1>
</template>

<script>
export default {
  name: "Messages",
  props: {
    msg: String,
  },
  data() {
    return {
      count: 0,
    };
  },
};
</script>
