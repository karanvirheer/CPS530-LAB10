<template>
  <div class="home">
    <HelloWorld />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HomePage.vue";

export default {
  name: "HomePage",
  components: {
    HelloWorld,
  },
};
</script>
