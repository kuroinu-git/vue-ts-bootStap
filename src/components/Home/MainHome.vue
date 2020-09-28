<template>
  <div class="grid">
    <div class="grid__item grid__item--lg">
      <div class="caption">
        <br />
        <h1>Aspect ratio grid - now with variable ratios!</h1>
        <br />
        <p>I noticed that using the CSS aspect ratio hack was causing issues with CSS Grid</p>
        <br />
        <button type="button" class="btn btn-outline-light btn--s">Popular</button>
      </div>
      <img
        src="https://images.unsplash.com/photo-1509408895711-7eda6e83c637?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=1844cab997dc2e5f1ce14e3b9cbd0bc1&auto=format&fit=crop&w=1500&q=80"
        alt="Starry sky"
        class="img--rounded--lg"
        width="100%"
        height="100%"
        display="block"
        object-fit="cover"
      />
    </div>

    <div class="grid__item grid__item--sm">
      <div class="caption--sm">
        <p class="card-text">24 items</p>
        <br />
        <h2>MEMEMEMM</h2>
        <br />
        <br />
      </div>
         <img
        src="https://images.unsplash.com/photo-1509408895711-7eda6e83c637?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=1844cab997dc2e5f1ce14e3b9cbd0bc1&auto=format&fit=crop&w=1500&q=80"
        alt="Starry sky"
        class="img--rounded--lg"
        width="100%"
        height="100%"
        display="block"
        object-fit="cover"
      />
    </div>

    <div class="grid__item grid__item--sm">
      <div class="caption--sm--s">
        <button type="button" class="btn btn-outline-light btn--s">NEW</button>
        <br />
        <br />
        <br />
        <br />
        <br />
        <h2>MEMEMEMM</h2>
      </div>
         <img
        src="https://images.unsplash.com/photo-1509408895711-7eda6e83c637?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=1844cab997dc2e5f1ce14e3b9cbd0bc1&auto=format&fit=crop&w=1500&q=80"
        alt="Starry sky"
        class="img--rounded--lg"
        width="100%"
        height="100%"
        display="block"
        object-fit="cover"
      />
    </div>

    <div class="grid__item grid__item--db">
      <div class="caption--lg--s">
        <button type="button" class="btn btn-outline-light btn--s">NEW</button>
        <br />
        <br />
        <br />
        <br />
        <br />
        <br />
        <h2>MEMEMEMM</h2>
      </div>
      <img
        src="https://images.unsplash.com/photo-1509408895711-7eda6e83c637?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=1844cab997dc2e5f1ce14e3b9cbd0bc1&auto=format&fit=crop&w=1500&q=80"
        alt="Starry sky"
        class="img--rounded--lg"
        width="100%"
        height="300px"
        display="block"
        object-fit="cover"
      />
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