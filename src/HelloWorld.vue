<script setup>
import axios from 'axios';
import { ref, onMounted } from 'vue';

import.meta.env.VUE_APP_MY_TMDBAPI_KEY

const movies = ref([])

const fetchMovies = async () => {
    const response = await axios.get('https://api.themoviedb.org/3/movie/popular', {
        headers: {
            Authorization: `Bearer ${import.meta.env.VITE_MY_TMDBAPI_KEY

        }
    })
}







</script>

<template>
  
</template>

<style scoped></style>