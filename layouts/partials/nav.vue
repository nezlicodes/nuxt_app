<template>
  <div>
  <b-navbar toggleable="lg" type="light" variant="light">
    <b-navbar-brand><nuxt-link to="/">NavBar</nuxt-link></b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>

      <!-- Right aligned nav items -->
       
      <b-navbar-nav class="ml-auto">

        <b-nav-item> <nuxt-link to="about"> A propos</nuxt-link></b-nav-item>
        <b-nav-item> <nuxt-link to="/contact"> Contact</nuxt-link></b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
</template>

<script>
export default {
    
}
</script>

<style lang="">
    
</style>