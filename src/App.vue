<template>
  <div id="app">
    <div id="cover">
      <Header></Header>
      <Todo></Todo>
      <Footer></Footer>
    </div>
  </div>
</template>

<script>
import Header from './todo/Header.vue'
import Footer from './todo/Footer.vue'
import Todo from './todo/Todo.vue'
export default {
  components: {
    Header,
    Footer,
    Todo,
  }
};
</script>

<style>
#app {
  position: absolute;
  height: 100%;
  width: 100%;
}

#cover {
  position: absolute;
  background-color: #999;
  opacity: 0.7;
  z-index: 10;
  width: 100%;
  height: 100%;
}
</style>
