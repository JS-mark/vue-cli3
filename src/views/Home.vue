<template>
  <div class="home">
    <child @hook:ddd="dd"></child>
  </div>
</template>

<script>
// @ is an alias to /src
import child from "@/components/child.vue";

export default {
  name: "home",
  components: {
    child
  },
  methods: {
    dd() {
      console.log("dasdadasd");
    }
  }
};
</script>
