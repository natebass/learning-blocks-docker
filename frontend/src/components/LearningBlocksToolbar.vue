<template>
  <v-app-bar :elevation="4" class="bg-blue-lighten-1">
    <template v-slot:prepend>
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
    </template>
    <v-app-bar-title style="cursor: pointer" @click="$router.push('/report')">
      Learning Blocks
    </v-app-bar-title>
    <v-spacer></v-spacer>
    <v-btn>Aries</v-btn>
  </v-app-bar>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component
export default class LearningBlocksToolbar extends Vue {
  public links = ["Home", "About Us", "Team", "Services", "Blog", "Contact Us"];
}
</script>

<style scoped>

</style>