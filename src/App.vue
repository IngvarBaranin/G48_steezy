<template>
  <v-app>
              <Navbar/>
              <Sidebar/>
  </v-app>
</template>

<script>
import Sidebar from './components/Sidebar';
import Navbar from './components/Topbar';

export default {
  name: 'App',

  components: {
    Sidebar,
      Navbar
  },

  data: () => ({
    //
  }),
};
</script>

<style>
body {
    width: 1200px;
    margin:0 auto;
}
</style>
