<template>
  <v-app>
  <div>
    <app-header></app-header>
    <hr>
    <app-server></app-server>
    <app-server-details></app-server-details>
    <hr>
    <app-footer></app-footer>
  </div>
  </v-app>
</template>

<script>
  import '@fortawesome/fontawesome-free/css/all.css'
  import header from './header.vue';
  import server from './server.vue';
  import serverDetails from './serverDetails.vue';
  import footer from './footer.vue';

export default {
  name: 'App',
  components: {
    'app-header' : header,
    'app-server' : server,
    'app-serverDetails' : serverDetails,
    'app-footer': footer,
  },
  props:{
    currentServerStatus: {
      default: `Server Details: `
    }
  },
  data: () => ({
    //
  }),
};
</script>
