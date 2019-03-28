<template>
  <div id="app">
    <navigation-bar></navigation-bar>
    <banner></banner>
    <articles></articles>
  </div>
</template>

<script>
import NavigationBar from "./components/Navigation/NavBar";
import Banner from "./components/Banner";
import Articles from "./components/Articles/Articles";

export default {
  components: {
    NavigationBar,
    Banner,
    Articles
  }
}
</script>
