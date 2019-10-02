<template>
  <v-app>
  <div>
    <app-header></app-header>
    <hr>
    <v-container>
      <v-row>
        <v-col>
    <app-server></app-server>
        </v-col>
        <v-col>
    <app-serverDetails></app-serverDetails>
        </v-col>
    </v-row>
    </v-container>
    <hr>
    <app-footer></app-footer>
  </div>
  </v-app>
</template>

<script>


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
