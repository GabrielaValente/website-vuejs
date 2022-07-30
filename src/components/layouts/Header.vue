<template>
  <div>
    <v-app-bar color="#06283D" dark elevation="0">
      <img class="img__logo" src="../.././assets/logo.svg" alt="Logo" />

      <Menu />

      <v-spacer></v-spacer>

      <div class="h__search__container">
        <v-text-field
          label="Buscar no site"
          rounded
          outlined
          append-icon="search"
          hide-details
          dense
        ></v-text-field>
      </div>
    </v-app-bar>
  </div>
</template>
<script>
import Menu from "./HeaderMenu.vue";

export default {
  components: {
    Menu,
  },
};
</script>

<style>
.img__logo {
  height: 20px;
  width: 20px;
}

.h__search__container {
  max-width: 330px;
}
</style>
