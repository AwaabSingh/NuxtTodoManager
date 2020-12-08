<template>
  <div class="container">
       <add-todo/>
       <filter-todo/>
       <todos-list/>
       
       
  </div>
</template>

<script>
  
import TodosList from '../components/TodosList.vue';
import AddTodo from '../components/AddTodo.vue';
import FilterTodo from '../components/FilterTodo.vue';
export default {
    components: {
        TodosList,
        AddTodo,
        FilterTodo
    }
}
</script>

<style>
 body {
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
  line-height: 1.6;
  background: #e8f7f0;
}
.container {
  max-width: 1100px;
  margin: auto;
  margin-top: 10px;
  overflow: auto;
  padding: 0 2rem;
}
</style>
