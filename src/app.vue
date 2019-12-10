<template>
  <div id="app">
    <div id="cover"></div>
    <Header></Header>
    <todo></todo>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from './todos/header.vue'
import Footer from './todos/footer.jsx'
import Todo  from './todos/todo.vue'


export default {
    components:{
        Header,
        Footer,
        Todo,
    }
};
</script>


<style lang="stylus" scoped>
#app {
  position: absolute;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;

  #cover {
    position: absolute;
    left: 0;
    right: 0;
    top: 0;
    bottom: 0;
    background-color: #999;
    opacity: 0.2;
    z-index: -1;
  }
}
</style>