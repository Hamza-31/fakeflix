<template>
  <div>
    <div v-for="movie in movies" v-bind:key="movie">
      <img :src="'https://image.tmdb.org/t/p/w500/' + movie.backdrop_path" />
      <h2>{{ movie.title }}</h2>
    </div>
  </div>
</template>


<script>
export default {
  name: "SearchResult",
};
</script>



<style scoped>
</style>
