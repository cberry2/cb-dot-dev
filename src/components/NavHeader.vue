<template>
  <v-app-bar app :class="darkMode ? 'theme--dark' : 'theme--light'">
    <v-toolbar-title class="headline text-uppercase">
      <span>CB</span>
      <span class="font-weight-light">.DEV</span>
    </v-toolbar-title>
    <v-spacer></v-spacer>
    <v-btn
      :class="darkMode ? 'theme--dark' : 'theme--light'"
      text
      href="https://github.com/cberry-chwy"
      target="_blank"
    >
      <span class="mr-2">Github</span>
    </v-btn>
    <v-btn
      :class="darkMode ? 'theme--dark' : 'theme--light'"
      text
      href="https://www.linkedin.com/in/craig-berry-0b329220/"
      target="_blank"
    >
      <span class="mr-2">LinkedIn</span>
    </v-btn>
      <v-switch
        class="nav-switch"
        :class="darkMode ? 'theme--dark' : 'theme--light'"
        v-model="darkMode"
        color="grey"
        inset
      ></v-switch>
  </v-app-bar>
</template>

<script>
export default {
  name: 'Header',
  data() {
    return {
      darkMode: false,
    };
  },
};
</script>

<style scoped>
  .v-toolbar .v-input.nav-switch {
   width: 150px;
   margin-top: 23px;
 }
</style>
