<template>
  <div>
    <p> {{ message }}</p>
  </div>
</template>

<script>
export default {
  name: "Paragraph",
  props: {
    message: String,
  }
}
</script>

<style scoped>
p {
  text-indent: 20pt;
  font-size: 20px;
  text-align: justify;
}
</style>
