<template>
  <div id="app">
    <Todos v-bind:todos="todos" ></Todos>
  </div>
</template>

<script>
  import Todos from "./components/Todos";

export default {
  name: 'App',
  components: {
    Todos
  },
  data() {
    return {
      todos: [
        {
          id: 1,
          title: "Finish this test app",
          completed: true
        },
        {
          id: 2,
          title: "Finish portfolio vueapp",
          completed: false
        },
        {
          id: 3,
          title: "Get internship",
          completed: false
        }      
      ]
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
