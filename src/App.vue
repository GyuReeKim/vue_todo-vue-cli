<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <!-- <HelloWorld msg="hello vue"/> -->
    <LoginForm/>
    <TodoList/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import TodoList from './components/TodoList.vue'
import LoginForm from './components/LoginForm.vue'

export default {
  name: 'app',
  components: {
    // HelloWorld,
    // 등록을 해야 에러가 없어진다.
    TodoList,
    LoginForm
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
