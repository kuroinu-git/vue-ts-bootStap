<template>
  <div class="app container">
    <Headshope />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import Headshope from '@/components/Shop/HeadShope.vue';

@Component({
  components: {
    Headshope,
  },
})
export default class Shop extends Vue {}
</script>