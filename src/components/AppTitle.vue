<template>
  <div>
    <h1>{{ titleText }}</h1>
  </div>
</template>

<script>
export default {
  name: "AppTitle",
  data: function () {
    return {
      titleText: "La Mia prima app con Vue CLI",
    };
  },
};
</script>

<style scoped></style>
