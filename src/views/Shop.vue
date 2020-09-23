<template>
  <div class="app container">
    <h1>MEMEMEMEMEEMEM</h1>
    <HeadShope msg="MEEMEMEMEM_MSG" />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import HeadShope from '@/components/Shop/HeadShope.vue';

@Component({
  components: {
      HeadShope,
  },
})
export default class Shop extends Vue {}
</script>