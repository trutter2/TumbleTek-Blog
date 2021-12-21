<template>

  <nav>
    <div class="nav-wrapper">
      <a href="#" class="brand-logo center">
            <img class="img-responsive" :src="logo" alt="TumbleTek TumbelTech logo" > 
            </a>
      <ul id="nav-mobile" class="left hide-on-med-and-down">
        <li><a href="sass.html">Sass</a></li>
      </ul>
      <ul id="nav-mobile" class="right hide-on-med-and-down">
        <li><a href="sass.html">Login</a></li>
      </ul>
    </div>
  </nav>

</template>

<script>
    import logo from '../assets/TumbleTek-Logo.png'

    export default {
        data: function() {
            return {
            logo: logo
            }
        }
    }

</script>


<style scoped>
.nav-wrapper {
    background-color: rgb(177, 177, 177);
}
.img-responsive {
    height: auto;
    width: auto;
    max-height: 60px;
    max-width: 200px;
    vertical-align: top;
}
</style>