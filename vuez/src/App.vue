<template>
  <div id="app">
    <div class="container">
        <nav class="navbar is-transparent" role="navigation" aria-label="main navigation">
            <div class="navbar-end">
                <a class="navbar-item" href="http://github.com/zorexsalvo"><span class="icon"><i class="fa fa-lg fa-github"></i></span></a>
                <a class="navbar-item" href="http://github.com/zorexsalvo"><span class="icon"><i class="fa fa-lg fa-twitter"></i></span></a>
                <a class="navbar-item" href="http://github.com/zorexsalvo"><span class="icon"><i class="fa fa-lg fa-facebook"></i></span></a>
            </div>
        </nav>
    </div>

    <router-view/>

    <br>
    <footer class="footer">
        <div class="container">
            <div class="content has-text-centered">
                <p>
                A blog <strong>site</strong> by <a href="https://zorexsalvo.com">@zorexsalvo</a>.
                </p>
            </div>
        </div>
    </footer>

  </div>
</template>

<script>
export default {
  name: 'app',
};
</script>

<style lang="css">
  @import "../node_modules/bulma/css/bulma.css";
  @import "https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css";
</style>
