<template>
  <footer>
    <h4>Real estate agency</h4>
    <address>
      Zahradni street 333<br />
      11150 Prague
    </address>
    <a href="tel:00420123456789">00420 123 456 789</a>
    <a href="mailto:myemail@gmail.com">myemail@gmail.com</a>
  </footer>
</template>

<script>
export default {
  name: "Header",
  props: {
    msg: String
  }
};
</script>

<style scoped></style>
