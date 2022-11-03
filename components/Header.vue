<template>
  <header class="sans-serif">
    <div class="bg-purple">
      <nav class="dt w-100 mw8 ph4 center">
<!--        <div class="dtc w5 v-mid pa3">
          <a href="/" class="border-box">
            <div class="dtc">
              <img src="http://tachyons.io/img/logo.jpg" class="br-100 pa1 ba b--black-10 h3 w3" alt="avatar">
            </div>
          </a>
        </div> -->
        <div class="dtc v-mid">
          <NuxtLink class="no-underline" to="/"><h1 class="f5 f4-ns fw6 white-80">Oliver Bates</h1></NuxtLink>
        </div>
        <div class="dtc v-mid">
          <h2 class="f6 fw2 ttu tracked white-90">Researcher, Designer, Social Tech</h2>
        </div>
        <div class="dtc v-mid tr pa3">
          <NuxtLink class="f6 fw4 hover-white no-underline white-70 dn dib-ns pv2 ph3" to="/">About</NuxtLink>
          <NuxtLink class="f6 fw4 hover-white no-underline white-70 dn dib-ns pv2 ph3" to="/now">Now</NuxtLink>
          <!--<a class="f6 fw4 hover-white no-underline white-70 dn dib-ns pv2 ph3" href="projects" >Projects</a>-->
          <a class="f6 fw4 hover-white no-underline white-70 dib ml2 pv2 ph3 ba" href="#contact" >Contact</a>
        </div>
      </nav>
    </div>
  </header>


</template>

<script>
export default {
  name: "Header.vue"
}
</script>

<style scoped>

</style>
