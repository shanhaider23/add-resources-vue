<template>
  <stored-resources :resources="storedResources"></stored-resources>
</template>

<script>
import StoredResources from './components/Resources/StoredResources.vue';
export default {
  components: {
    StoredResources,
  },
  data() {
    return {
      storedResources: [
        {
          id: 'offical-guide',
          title: 'Offical Guide',
          description: 'The offical vue.js guide',
          link: 'https://v2.vuejs.org/v2/style-guide/?redirect=true#Priority-A-Essential',
        },
        {
          id: 'google',
          title: 'Offical Guide',
          description: 'The offical vue.js guide',
          link: 'https://v2.vuejs.org/v2/style-guide/?redirect=true#Priority-A-Essential',
        },
      ],
    };
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

* {
  box-sizing: border-box;
}

html {
  font-family: 'Roboto', sans-serif;
}

body {
  margin: 0;
}
</style>