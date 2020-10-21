<template>
  <v-app>
    <v-main>
      <TheMinistryOfEducation/>
    </v-main>
  </v-app>
</template>

<script>
import TheMinistryOfEducation from './components/TheMinistryOfEducation';

export default {
  name: 'App',

  components: {
    TheMinistryOfEducation,
  },

  data: () => ({
    //
  }),
};
</script>
