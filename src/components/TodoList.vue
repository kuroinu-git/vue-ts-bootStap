<template class="change-background-color">
  <div class="todolist">
    <h1>{{ msg }}</h1>
    <div class="input-group mb-3">
      <input
        type="text"
        class="form-control"
        placeholder="Todo"
        aria-label="Todo"
        aria-describedby="button-addon2"
        v-model="todoInput"
      />
      <div class="input-group-append">
        <button
          class="btn btn-outline-secondary"
          type="button"
          id="button-addon2"
          @click="addTodo"
        >ADD</button>
      </div>
    </div>

    <ul>
      <li
        v-for="(todo,index) in todoList"
        :key="index"
        :class="{
        'list-group-item': true,
        'list-group-item-secondary': todo.checked
      }"
        @click="todo.toggleChecked()"
      >
        {{todo.todo}}
        <button
          type="button"
          class="close"
          data-dismiss="modal"
          aria-label="Close"
          @click.stop="delTodo(todo)"
        >
          <span aria-hidden="true">&times;</span>
        </button>
      </li>
    </ul>
  </div>
</template>

<script lang='ts'>
import { Component, Prop, Vue } from 'vue-property-decorator';
import '@/assets/styless/todoList.scss';

class Todo {
  todo: string;
  checked: boolean;

  constructor(todo: string) {
    this.todo = todo;
    this.checked = false;
  }

  toggleChecked() {
    this.checked = !this.checked;
  }
}
@Component({})
export default class TodoList extends Vue {
  @Prop() private msg!: string;

  todoInput: string = '';
  todoList: Todo[] = [];

  addTodo() {
    console.log('todoInput:', this.todoInput);
    const todo = new Todo(this.todoInput);
    this.todoList.push(todo);
  }
  beforeUpdate() {
    console.log('before update');
  }
  delTodo(todo: Todo) {
    console.log('delTodo: ', todo);
    this.todoList = this.todoList.filter((todoItem) => {
      return todoItem !== todo;
    });
  }

  mounted() {
    this.todoList.push(new Todo('woowww'));
    this.todoList.push(new Todo('WTF'));
  }
}
</script>
