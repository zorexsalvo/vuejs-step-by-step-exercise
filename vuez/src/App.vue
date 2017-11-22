<template>
  <div id="app">
    <div class="container">
        <nav class="navbar" role="navigation" aria-label="main navigation">
            <div class="navbar-brand">
                <a class="navbar-item" href="">
                    <img src="./assets/images/vuez-logo.png" alt="">
                </a>
                <router-link class="navbar-item" to="/">Home</router-link>
            </div>
        </nav>
    </div>

    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'app',
};
</script>

<style lang="css">
  @import "../node_modules/bulma/css/bulma.css";
</style>
