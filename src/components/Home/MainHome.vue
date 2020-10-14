<template>
  <div class="container-main-home">
    <div class="frontpage">
      <div class="fp-cell fp-cell--1">
          <div class="caption-lg-background">
        <div class="fp-item">
            <div class="caption-lg">
              <br />
              <h1 class="caption-lg-serif">
                Aspect ratio grid - now with variable ratios!
              </h1>
              <br />
              <p>
                I noticed that using the CSS aspect ratio hack was causing
                issues with CSS Grid
              </p>
              <br />
              <button type="button" class="btn btn-main">Popular</button>
            </div>
          </div>
        </div>
      </div>

      <div class="fp-cell fp-cell--3">
          <div class="caption-sm-background">
        <div class="fp-item">
            <div class="caption-sm">
              <p>24 items</p>
              <div class="caption-sm-new-line"></div>
              <h2 class="caption-sm-serif">MEMEMEMM</h2>
            </div>
          </div>
        </div>
      </div>

      <div class="fp-cell fp-cell--4">
          <div class="caption-sm-s-background">
        <div class="fp-item">
            <div class="caption-sm-s">
              <button type="button" class="btn btn-main">NEW</button>
              <div class="caption-sm-s-new-line"></div>
              <h2 class="caption-sm-s-serif">MEMEMEMM</h2>
            </div>
          </div>
        </div>
      </div>

      <div class="fp-cell fp-cell--2">
          <div class="caption-lg-s-background">
        <div class="fp-item">
            <div class="caption-lg-s">
              <button type="button" class="btn btn-main">NEW</button>
              <div class="caption-lg-s-new-line"></div>
              <h2 class="caption-lg-s-serif">MEMEMEMM</h2>
            </div>
          </div>
        </div>
      </div>

    </div>
  </div>
</template>
<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';
import '@/assets/styless/mainHome.scss';

@Component
export default class MainHome extends Vue {
  @Prop() private msg!: string;
}
</script>