<template>
  <v-app>
    <default-system-bar v-if="false" />

    <default-explore-system-bar />

    <home-bar />

    <home-view />

    <home-footer />

    <!-- <default-snackbar /> -->

    <default-settings />
  </v-app>
</template>

<script>
  // Components
  import DefaultSettings from '@/layouts/default/settings/Settings'
  // import DefaultSnackbar from '@/layouts/default/Snackbar'
  import DefaultSystemBar from '@/layouts/default/SystemBar'
  import DefaultExploreSystemBar from '@/layouts/default/ExploreSystemBar'
  import HomeBar from './AppBar'
  import HomeFooter from './Footer'
  import HomeView from './View'

  export default {
    name: 'HomeLayout',

    components: {
      DefaultSettings,
      DefaultExploreSystemBar,
      DefaultSystemBar,
      // DefaultSnackbar,
      HomeBar,
      HomeFooter,
      HomeView,
    },
  }
</script>
