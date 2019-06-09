<template>
  <div id="app">
    <Main/>
  </div>
</template>

<script>
import Main from "./components/Main";

export default {
  name: "App",
  components: {
    Main
  }
};
</script>

<style lang="scss">
// variables
@import "./css/variables/variables.scss";
@import "./css/variables/colors.scss";
/* font */
@font-face {
  font-family: "Andale Mono Regular";
  font-style: normal;
  font-weight: normal;
  src: local("Andale Mono Regular"),
    url("./assets/ANDALEMO.woff") format("woff");
}
</style>
