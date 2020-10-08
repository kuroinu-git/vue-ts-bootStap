<template>
  <div class="head">
    <header class="headimage text-white rounded bg-primary">
      <div class="container-fluid w-100 headhome">
        <div class="col-md-6 px-0">
          <h1 class="display-4 text-white">Business Name or Tagline MEMEMEME</h1>
          <br />
          <p
            class="lead my-3"
          >Multiple lines of text that form the lede, informing new readers quickly and efficiently about what's most interesting in this post's contents.</p>
          <br />
          <button type="button" class="btn btn-outline-light btn-lg-h">Show More</button>
        </div>
      </div>
    </header>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';
import '@/assets/styless/headHome.scss';

@Component
export default class HeaderHome extends Vue {}
</script>

