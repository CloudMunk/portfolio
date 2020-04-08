<template>
  <v-app dark>
    
    <v-app-bar
      :clipped-left="clipped"
      fixed
      app
      color="indigo"
    >
      <v-spacer />
      <v-toolbar-title v-text="title" />
      <v-spacer />
    </v-app-bar>
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>
    <v-footer
      :fixed="fixed"
      app
    >
      <span>&copy; 2020</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  data () {
    return {
      clipped: true,
      fixed: true,
      title: 'Anestis Finstad'
    }
  }
}
</script>
