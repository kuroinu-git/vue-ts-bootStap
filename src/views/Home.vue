<template>
  <div class="home">
    <Headhome msg="MEMEMEMEMEMEMEMEM" />
    <Mainhome msg="MEMEMEMEMEMEMEMEM" />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import Headhome from '@/components/Home/HeaderHome.vue';
import Mainhome from '@/components/Home/MainHome.vue';

@Component({
  components: {
    Headhome,
    Mainhome,
  },
})
export default class Home extends Vue {}
</script>
