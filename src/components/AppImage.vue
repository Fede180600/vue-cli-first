<template>
  <div>
    <img :src="require(`../assets/img/${imgSrc}`)" alt="" />
  </div>
</template>

<script>
export default {
  name: "AppImage",
  data: function () {
    return {
      imgSrc: "Roma.jpg",
    };
  },
};
</script>
<style>
img {
  max-width: 450px;
}
</style>
