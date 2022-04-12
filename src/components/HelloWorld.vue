<template>
  <div>
    <p>Hello {{ value }}</p>
  </div>
</template>

<script>
export default {
  names: 'hello-world',
  value: 'hello-world',
  props: {
    name: {
      type: String,
      required: true,
    },
  },
};
</script>

<style scoped></style>
