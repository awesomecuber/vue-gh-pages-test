<template lang="pug">
v-app
  v-navigation-drawer(app)
    p hi
  v-app-bar(app)
    p hello
  v-content
    v-container(fluid)
      h1 hello
  v-footer(app)
    p goodbye
</template>

<script>
export default {
  name: "App",
  data: () => ({
    //
  })
};
</script>
