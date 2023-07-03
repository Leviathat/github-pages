<template>
  <div class="skills" id="skills">
    <span class="skills-title">Skills</span>
    <ul class="skills-list">
      <li>
        Backend:
        <ul class="skill">
          <li class="skills-item">Django + DRF</li>
          <li class="skills-item">FastAPI</li>
        </ul>
      </li>
      <li>
        DevOps:
        <ul class="skill">
          <li class="skills-item">Linux</li>
          <li class="skills-item">Docker</li>
          <li class="skills-item">PSQL</li>
          <li class="skills-item">Nginx</li>
        </ul>
      </li>
      <li>
        Frontend:
        <ul class="skill">
          <li class="skills-item">Vue 3 + VueX</li>
          <li class="skills-item">Tailwind CSS</li>
        </ul>
      </li>
    </ul>
  </div>
</template>
<script>
export default {
  name: "MySkills",
};
</script>
<style scoped>
.skills {
  margin-top: 2em;
  padding: 1em 2em;
  background: #000;
  color: tomato;
}
.skills-title {
  font-family: "Libre Caslon Text", sans-serif;
  font-weight: 500;
  color: #fff;
  font-size: 2em;
}
.skills-list {
  font-family: "Libre Caslon Text", serif;
  font-size: 1.5em;
}
.skills-item {
  text-indent: -5px;
  padding: 0.3em 0;
  list-style-type: none;
  color: #fff;
}
.skills-item:before {
  content: "- ";
  text-indent: -5px;
}
</style>
