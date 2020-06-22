<template>
  <section>
    <img src="../assets/hero.jpg" alt="flat3" />
    <div>
      <h1>
        {{ title }}
      </h1>
      <a href="#properties">Check our properties</a>
    </div>
  </section>
</template>

<script>
export default {
  name: "Landing",
  props: {
    title: String
  }
};
</script>

<style scoped></style>
