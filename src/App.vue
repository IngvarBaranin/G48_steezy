<template>
  <v-app>
      <v-container>
          <Navbar/>
          <Sidebar/>
      </v-container>




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

