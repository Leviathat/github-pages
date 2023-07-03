<template>
  <div class="education" id="edu">
    <span class="edu-title">Education</span>
    <ul class="edu-list">
      <li class="edu-item">
        <a href="https://intc.kz/en/" class="edu-link">IT College</a>, graduated
        in 2022
      </li>
      <li class="edu-item">
        <a href="https://iitu.edu.kz/en/" class="edu-link"
          >International IT University</a
        >, 2022 - 2025
      </li>
    </ul>
  </div>
</template>
<script>
export default {
  name: "MyEducation",
};
</script>
<style scoped>
.education {
  margin-top: 2em;
  padding: 1em 2em;
  background: #000;
  color: #fff;
}
.edu-title {
  font-family: "Libre Caslon Text", sans-serif;
  font-weight: 500;
  color: #fff;
  font-size: 2em;
}
.edu-list {
  font-family: "Libre Caslon Text", serif;
  font-size: 1.5em;
  list-style-type: none;
}
.edu-item {
  text-indent: -5px;
  padding: 0.3em 0;
}
.edu-link {
  color: tomato;
  padding: 0.1em 0;
  text-decoration: none;
}
.edu-link:hover {
  border-bottom: #fff 0.1em solid;
}
.edu-item:before {
  content: "- ";
  text-indent: -5px;
}
</style>
