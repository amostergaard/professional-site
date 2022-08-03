<template>
  <v-app>
    <v-app-bar fixed app>
      <v-toolbar-title>Amelia Ostergaard Portfolio</v-toolbar-title>
      <v-spacer />
      <nuxt-link to="/">Home</nuxt-link>
    </v-app-bar>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
    <v-footer app>
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: 'DefaultLayout',
}
</script>
