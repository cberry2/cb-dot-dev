<template>
  <v-app>
    <v-app-bar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>CB</span>
        <span class="font-weight-light">.DEV</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn
        text
        href="https://github.com/cberry2"
        target="_blank"
      >
        <span class="mr-2">Github</span>
      </v-btn>
    </v-app-bar>

    <v-content>
      <v-container fluid
                   class="fill-height">
        <HelloWorld/>
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
  data: () => ({
    //
  }),
};
</script>
