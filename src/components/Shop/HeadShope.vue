<template>
  <div>
    <div class="flex-container">
      <div class="item small">1</div>
      <div class="item big">2</div>
      <div class="item mediam">3</div>
    </div>
    <div style="height: 40px"></div>
    <div class="grid-container">
      <div>1</div>
      <div>2</div>
      <div>3</div>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';
import '@/assets/styless/flex.scss';
@Component({})
export default class HeadShope extends Vue {
  @Prop() private msg!: string;
}
</script>