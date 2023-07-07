<template>
  <div class="exp" id="exp">
    <span class="exp-title">Experience</span>
    <ul class="exp-list">
      <li>
        Kassa 24 / 7:
        <ul class="skill">
          <li class="exp-item">
            JWT token based Auth service on Django and DRF
          </li>
          <li class="exp-item">Containerizing App and Redis with Docker</li>
          <li class="exp-item">CI / CD in Gitlab</li>
        </ul>
      </li>
      <li>
        BP Contact:
        <ul class="skill">
          <li class="exp-item">Django ORM optimization for CRM projects</li>
          <li class="exp-item">Maintaining projects on Prod.</li>
          <li class="exp-item">Deploying projects</li>
        </ul>
      </li>
    </ul>
  </div>
</template>
<script>
export default {
  name: "MyExperience",
};
</script>
<style scoped>
.exp {
  margin-top: 2em;
  padding: 1em 2em;
  background: #000;
  color: tomato;
}
.exp-title {
  font-family: "Libre Caslon Text", sans-serif;
  font-weight: 500;
  color: #fff;
  font-size: 2em;
}
.exp-list {
  font-family: "Libre Caslon Text", serif;
  font-size: 1.5em;
}
.exp-item {
  text-indent: -5px;
  padding: 0.3em 0;
  list-style-type: none;
  color: #fff;
}
.exp-item:before {
  content: "- ";
  text-indent: -5px;
}
</style>
