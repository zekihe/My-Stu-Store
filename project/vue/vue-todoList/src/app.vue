<template>
  <div id="app">
    <div id="cover"></div>
    <commonHeader></commonHeader>
    <Todo></Todo>
    <commonFooter></commonFooter>
  </div>
</template>

<script>
import commonHeader from './todo/header.vue'
import commonFooter from './todo/footer.jsx'
import Todo from './todo/todo.vue'


export default {
  data(){
    return {
      
    }
  },
  components: {
    commonHeader,
    Todo,
    commonFooter,
  }
}
</script>

<style lang="stylus" scoped>
#app{
  position absolute
  left 0
  right 0
  top 0
  bottom 0
}
#cover{
  position absolute
  left 0
  top 0
  right 0
  bottom 0
  background-color #999
  opacity .6
  z-index -1
}
</style>
