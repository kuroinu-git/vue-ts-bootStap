<template>
  <div class="app container">
    <h1>Todo list + TS</h1>
    <TodoList msg="Todo list"/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import TodoList from '@/components/TodoList.vue'; // @ is an alias to /src


@Component({
  components: {
      TodoList,
  },
})
export default class Todo extends Vue {}
</script>