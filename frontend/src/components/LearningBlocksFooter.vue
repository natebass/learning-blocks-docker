<template>
  <v-footer class="bg-blue-lighten-1">
    <v-row justify="center" no-gutters>
      <v-btn
        v-for="link in links"
        :key="link"
        class="mx-2"
        color="white"
        rounded="xl"
        variant="text"
      >
        {{ link }}
      </v-btn>
      <v-col class="text-center mt-4" cols="12">
        {{ new Date().getFullYear() }} — <strong>Learning Blocks</strong>
      </v-col>
    </v-row>
  </v-footer>
</template>

<script lang="ts">
import { Vue } from "vue-property-decorator";

export default class AppToolbar extends Vue {
  /**
   * Returns the average of two numbers.
   *
   * @remarks
   * Route level code-splitting. This generates a separate chunk (about.[hash].js) for this route which is lazy-loaded
   * when the route is visited.
   * Example: /* webpackChunkName: "login" *\/
   *
   * @param x - The first input number
   * @param y - The second input number
   * @returns The arithmetic mean of `x` and `y`
   *
   * @beta
   */
  links = ["link1", "link2"];
}
</script>

<style scoped></style>
