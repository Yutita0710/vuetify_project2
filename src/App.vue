<template>
  <!-- <router-view /> -->
  <NavAppBar />
  <ListBar />
</template>

<script>
import NavAppBar from "./components/NavAppBar.vue";
import ListBar from "./components/ListBar.vue";

export default {
  name: "App",
  components: {
    NavAppBar,
    ListBar,
  },
};
</script>
