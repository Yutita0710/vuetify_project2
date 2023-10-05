<template>
  <NavAppBar />
  <Content />
  <Content1/>
</template>

<script>
import Content from "./components/Content.vue";
import NavAppBar from "./components/NavAppBar.vue";
import Content1 from "./components/Content1.vue";

export default {
  name: "App",
  components: {
    NavAppBar,
    Content,
    Content1,
  },
};
</script>
