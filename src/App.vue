<template>
  <v-app>
      <side-bar />
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
import sideBar from "./components/sideBar.vue";

export default {
  components: { sideBar },
  name: "App",

  data: () => ({
    //
  }),
};
</script>
