<template>
  <div class="home">
    <PageNavbar />
  </div>
</template>

<script>
// @ is an alias to /src
import PageNavbar from "@/components/PageNavbar.vue";

export default {
  name: "HomeView",
  components: {
    PageNavbar,
  },
};
</script>
