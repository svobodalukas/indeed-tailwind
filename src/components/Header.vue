<template>
  <nav>
    <a href="#">{{ projectName }}</a>
  </nav>
</template>

<script>
export default {
  name: "Header",
  props: {
    projectName: String
  }
};
</script>

<style scoped></style>
