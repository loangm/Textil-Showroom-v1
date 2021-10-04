<template>
  <v-app>
    <v-main>
      <HelloWorld/>
    </v-main>
      <Footer/>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import Footer from './components/Footer';

export default {
  name: 'App',

  components: {
    HelloWorld,
    Footer
  },

  data: () => ({
  }),
};
</script>
