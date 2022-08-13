<template>
  <main>
    <CoursesPrices />
    <PicturesGallery />
  </main>
</template>

<script>
import CoursesPrices from './components/CoursesPrices.vue';
import PicturesGallery from './components/PicturesGallery.vue';


export default {
  components: {
    CoursesPrices,
    PicturesGallery,
  },
};
</script>

<style>
* {
  box-sizing: border-box;
}

html {
  font-family: sans-serif;
}
main {
  display: flex;
  justify-content: center;
  column-gap: 50px;
  align-items: start;
  padding: 20px;
}
</style>