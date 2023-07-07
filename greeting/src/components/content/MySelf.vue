<template>
  <div class="bio-title">
    <span class="bio-title-text">
      Hello there!
      <br />
      I'm 20 years old Backend Developer
    </span>
    <div class="bio-image">
      <img src="../../assets/me.jpeg" alt="" />
    </div>
  </div>
</template>
<script>
export default {
  name: "MySelf",
};
</script>
<style scoped>
.bio-title {
  display: flex;
  box-sizing: border-box;
  flex-wrap: wrap;
  border-right: #000 0.35em solid;
}
.bio-title-text {
  flex: 1;
  padding: 1em;
  text-align: center;
  z-index: 15;
  font-family: "Libre Caslon Text", serif;
  color: #fff;
  background: #000;
  font-size: 2em;
}
.bio-image {
  z-index: 16;
  padding: 1em 1em 1em 0;
  margin: 0 auto;
}
@media (max-width: 1024px) {
  .bio-title {
    flex-direction: column;
    border-right: transparent 0 solid !important;
    border-bottom: #000 0.35em solid;
  }
}
</style>
