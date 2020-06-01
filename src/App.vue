<template>
  <div id="app">
    <HelloWorld></HelloWorld>
    <todo></todo>
  </div>
</template>

<script>
  import todo from "./components/todo";
  import HelloWorld from "./components/HelloWorld";

export default {
  name: 'App',
  components: {
    HelloWorld,
    todo
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
