<template>
  <div class="wrapper">
    <header>
      <header-title />
      <header-navbar />
    </header>
    <div class="content">
      <my-self />
      <my-education />
      <my-skills />
      <my-experience />
    </div>
  </div>
</template>

<script>
import HeaderTitle from "@/components/header/HeaderTitle.vue";
import HeaderNavbar from "@/components/header/HeaderNavbar.vue";
import MySelf from "./components/content/MySelf.vue";
import MyEducation from "@/components/content/MyEducation.vue";
import MySkills from "./components/content/MySkills.vue";
import MyExperience from "./components/content/MyExperience.vue";

export default {
  name: "App",
  components: {
    HeaderTitle,
    HeaderNavbar,
    MySelf,
    MyEducation,
    MySkills,
    MyExperience,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Libre+Caslon+Text&display=swap");

body {
  margin: 0 !important;
  padding: 0 !important;
  box-sizing: border-box;
  min-height: 100vh;
  min-width: 100vw !important;
  scroll-behavior: smooth;
}
.content {
  width: 100%;
  margin-top: 2em;
  padding: 0 !important;
  box-sizing: border-box;
}
#app {
  width: 70%;
  margin: 0 auto;
  padding: 0;
  box-sizing: border-box;
}
</style>
