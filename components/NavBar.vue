<template>
  <v-card class="overflow-hidden">
    <v-app-bar
      absolute
      color="white"
      elevate-on-scroll
      scroll-target="#scrolling-techniques-7"
    >
      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-toolbar-title>Gloria Rossi</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn >
        Case Studies
      </v-btn>

      <v-btn >
        Gallery
      </v-btn>

      <v-btn >
        About me
      </v-btn>

      <v-btn >
        My CV
      </v-btn>
    </v-app-bar>
    <v-sheet
      id="scrolling-techniques-7"
      class="overflow-y-auto"
      max-height="600"
    >
      <v-container style="height: 70px;">
      </v-container>
    </v-sheet>
  </v-card>
</template>

<script>
export default {
  name: "NavBar"
}
</script>

<style scoped>

</style>
