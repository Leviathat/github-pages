<template>
  <div class="header-navbar">
    <a href="#edu">Education</a>
    <a href="#skills">Skills</a>
    <a href="#exp">Experience</a>
  </div>
</template>
<script>
export default {
  name: "HeaderNavbar",
};
</script>
<style scoped>
.header-navbar {
  display: flex;
  flex-wrap: wrap;
  width: 100%;
  box-sizing: border-box;
  background: #000;
  padding: 1em;
}
.header-navbar a {
  text-decoration: none;
  margin: 0 1em 0 0;
  border-bottom: transparent 0.1em solid;
}
.header-navbar a:hover {
  border-bottom: #fff 0.1em solid;
}
a {
  font-family: "Libre Caslon Text", sans-serif;
  font-weight: 500;
  color: #fff;
  font-size: 2em;
}
</style>
