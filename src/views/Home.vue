<template>
  <div>
    <Intro></Intro>
    <Destinations></Destinations>
    <Testimonials></Testimonials>
    <News></News>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import Destinations from '@/components/Destinations.vue';
import Intro from '@/components/Intro.vue';
import News from '@/components/News.vue';
import Testimonials from '@/components/Testimonials.vue';

@Options({
  components: {
    Destinations,
    Intro,
    Testimonials,
    News,
  },
})
export default class Home extends  Vue {}
</script>

<style>

</style>
