<template>
  <div id="app" class="antialiased font-sans">
    <app-header projectName="Real estate"></app-header>
    <landing title="Best flats in the city!"></landing>
    <articles></articles>
    <app-footer></app-footer>
  </div>
</template>

<script>
import AppHeader from "./components/Header";
import Landing from "./components/Landing";
import Articles from "./components/Articles";
import AppFooter from "./components/Footer";

export default {
  name: "App",
  components: {
    AppHeader,
    Landing,
    Articles,
    AppFooter
  }
};
</script>

<style></style>
