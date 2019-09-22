<template>
  <v-app>

    <NavHeader/>


        <Home/>
  </v-app>
</template>

<script>
  import Home from './components/Home';
  import NavHeader from './components/NavHeader';

  export default {
    name: 'App',
    components: {
      Home, NavHeader,
    },
    data: () => ({
      //
    }),
  };
</script>
