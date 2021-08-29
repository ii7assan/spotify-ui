<template>
  <v-app>
      <side-bar />
    <v-main>
      <router-view />
    </v-main>
    <Footer />
  </v-app>
</template>

<script>
import Footer from './components/footer.vue';
import sideBar from "./components/sideBar.vue";

export default {
  components: { sideBar, Footer },
  name: "App",

  data: () => ({
    //
  }),
};
</script>
