<template>
  <v-app class="bg-grey">
    <default-bar />
    <default-view />
    <default-footer />
  </v-app>
</template>

<script lang="ts" setup>
  import DefaultBar from './AppBar.vue'
  import DefaultView from './View.vue'
  import DefaultFooter from './AppFooter.vue'
</script>
