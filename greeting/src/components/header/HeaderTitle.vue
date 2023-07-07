<template>
  <div class="header-title">
    <span>Mukanov Murager</span>
    <span class="justification"> Я Бэкендер - мне простительно</span>
  </div>
</template>
<script>
export default {
  name: "HeaderTitle",
};
</script>
<style scoped>
.header-title {
  width: 100%;
  box-sizing: border-box;
  background: #000;
  padding: 1em;
}
span {
  font-family: "Libre Caslon Text", serif;
  color: #fff;
  font-size: 3em;
}
.justification {
  text-indent: 5px;
  color: tomato;
  font-size: 1.5em;
}
</style>
