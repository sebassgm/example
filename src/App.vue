
<template>
  <v-content>
    <Toolbar />
    <v-main>
      <Search />
    </v-main>
    <h1>Esto funciona</h1>
  </v-content>
</template>

<script>
import Toolbar from './components/Toolbar';
import Search from './components/Search';

export default {
  name: "App",

  components: {
    Toolbar,
    Search,
  },

  data: () => ({
    //
  }),
};
</script>

<style scoped>
</style>