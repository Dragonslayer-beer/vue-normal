<template>
  <v-app>
    <Header />
    <Menu />
   <Contend />

  </v-app>
</template>

<script>
import Header from "@/components/core/Header.vue";
import Menu from "@/components/core/Menu.vue";
import Contend from "@/components/core/Contend.vue";
export default {
  name: "App",
  components: {
    Header,
    Menu,
    Contend
  },
};
</script>

<style></style>
