<template>
  <v-app>
    <v-main>
      <v-app-bar>
        <v-app-bar-title>PokeNotion</v-app-bar-title>
      </v-app-bar>
      <router-view />
    </v-main>
  </v-app>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "App",

  data() {
    return {
      //
    };
  },
});
</script>
