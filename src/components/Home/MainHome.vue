<template>
  <div class="container">
    <div class="row">
      <div class="col-lg d-flex flex-column">
        <div class="card">
          <div class="card-body h-100">
            <h4 class="card-title">.card-title</h4>
            <p
              class="card-text"
            >This is another panel with even more text content! Nullam sapien massa, aliquam in cursus ut, ullamcorper in tortor. Aliquam codeply mauris arcu, tristique a lobortis vitae, condimentum feugiat justo.</p>
            <a href="#" class="btn btn-primary">.btn-primary</a>
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