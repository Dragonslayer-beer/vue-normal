<template>
  <v-App>
    <Header v-if="$store.state.isLogged"/>
    <Menu v-if="$store.state.isLogged"/>
    <Content/>
  </v-App>
</template>

<script>
import Header from "@/components/core/Header";
import Menu from "@/components/core/Menu";
import Content from "@/components/core/Content";
export default {
  name: "App",
  components: {
    Header,
    Menu,
    Content
  },
};
</script>

<style></style>
