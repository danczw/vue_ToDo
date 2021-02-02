<template>
  <div id='app'>
    <div class="container">
      <AddTodo/>
      <FilterTodos/>
      <Todos/>
    </div>
  </div>
</template>

<script>
import Todos from './components/Todos.vue';
import AddTodo from './components/AddTodo.vue';
import FilterTodos from './components/FilterTodos.vue'

export default {
  name: 'app',
  components: {
    Todos,
    AddTodo,
    FilterTodos
  }
}
</script>

<style>
  body {
    font-family: 'Courier New', Courier, monospace;
    line-height: 1.5;
    background: whitesmoke;
  }

  .container {
    max-width: 1100px;
    margin: auto;
    overflow: auto;
    padding: 0 2rem;
    color: black;
  }
</style>
