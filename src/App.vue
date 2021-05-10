<template>
      <div id="app">
        <div class="card">
  <div class="card-header">
    made by Vue ||
    <a href="https://api.whatsapp.com/send?phone=6281394980082&text=Hi" class="btn btn-primary btn-sm">whatsapp +62 813 9498 0082</a>
<a class="btn btn-primary btn-sm" href="mailto:alditya676@gmail.com" id="down"  data-bs-toggle="tooltip" data-bs-placement="right" title="email"> email me</a>
  </div>
  <div class="card-body">
    <blockquote class="blockquote mb-0">
      <h1>My Todo App!</h1>
      <TodoList />
    </blockquote>
  </div>
  </div>
</div>
</template>

<script>
import TodoList from "./components/TodoList.vue";

export default {
  components: {
    TodoList,
  },
};
</script>

<style>

#app {
  max-width: 400px;
  margin: 0 auto;
  margin-top: 120px;
  line-height: 1.4;
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

h1 {
  text-align: center;
}
</style>