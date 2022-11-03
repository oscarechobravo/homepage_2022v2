<template>
  <div>
    <Header/>
    <div class="bg-light-pink mw8 center">
      <h1>
      My projects go here!
      </h1>
      <p>I've done a bunch of work over the years</p>
<!--      <li v-for="project in projects" :key="project.id">
        {{project.title}}
      </li>-->
      <Projects/>
    </div>
    <!--load pages/projects.json-->
    <!--loop through projects.json-->
    <!-- link these to md files -->
  </div>
</template>

<script>

export default {
  name: "projects",
};
</script>

<style scoped>


</style>
