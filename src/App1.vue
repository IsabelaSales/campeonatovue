<template>
  <v-app>
    <AppTopBar/>
    <v-main>
      <InicioI/>
    </v-main>
  </v-app>
</template>

<script>
import InicioI from './components/InicioI'
import AppTopBar from './components/shared/AppTopBar'

export default {
  name: 'App',
  components: {
    AppTopBar,
    InicioI,
  }
};
</script>
