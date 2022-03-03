<template>
  <pokemon-party />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import PokemonParty from "@/components/PokemonParty.vue";

export default defineComponent({
  name: "HomeView",
  components: {
    PokemonParty,
  },
});
</script>
