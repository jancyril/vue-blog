<template>
  <div class="navigation-bar">
    <nav class="navbar navigation-bar">
      <div class="container">
        <navigation-bar-brand></navigation-bar-brand>
        <navigation-bar-menu></navigation-bar-menu>
      </div>
    </nav>
  </div>
</template>

<script>
import NavigationBarBrand from "./NavBarBrand";
import NavigationBarMenu from "./NavBarMenu";

export default {
  components: {
    NavigationBarBrand,
    NavigationBarMenu
  }
};
</script>
