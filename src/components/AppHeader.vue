<template>
  <header class="app-header">
    <div class="container">
      <div class="site-header__right">
        <img src="../assets/gfx/drupal-commerce-logo.png" alt="Drupal Commerce">
        <span>The Adaptive Sales Platform</span>
      </div>
      <div class="site-header__logo">
        <img src="../assets/gfx/logo.png" alt="Commerce Kickstart">
      </div>
      <div class="site-header__slogan">
        The quickest way to get up & running with <span>Drupal Commerce 2</span> & <span>Drupal 8</span>
      </div>
    </div>
  </header>
</template>

<script>
  export default {
    name: 'app-header',
    data () {
      return {}
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
  @import '../assets/styles/partials/mixins';
  @import '../assets/styles/partials/variables';
  @import '../assets/styles/partials/header';
</style>
