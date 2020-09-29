<template>
  <div class="home">
    <Headhome msg="MEMEMEMEMEMEMEMEM" />
    <Mainhome msg="MEMEMEMEMEMEMEMEM" />
    <Caroueslhome msg="MEMEMEMEMEMEMEMEM" />
    <Likehome msg="MEMEMEMEMEMEMEMEM" />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import Headhome from '@/components/Home/HeaderHome.vue';
import Mainhome from '@/components/Home/MainHome.vue';
import Caroueslhome from '@/components/Home/CarouselHome.vue';
import Likehome from '@/components/Home/LikeHome.vue';

@Component({
  components: {
    Headhome,
    Mainhome,
    Caroueslhome,
    Likehome,
  },
})
export default class Home extends Vue {}
</script>
