<template>
  <div id="app">
    <todoHeader></todoHeader>
    <todoInput></todoInput>
    <todoList></todoList>
    <todoFooter></todoFooter>
  </div>
</template>

<script>
import todoHeader from './components/todoHeader.vue'
import todoInput from './components/todoInput.vue'
import todoList from './components/todoList.vue'
import todoFooter from './components/todoFooter.vue'
export default {
  components: {
    todoHeader:todoHeader,
    todoInput:todoInput,
    todoList:todoList,
    todoFooter:todoFooter,
  }
}
</script>

<style>

</style>
