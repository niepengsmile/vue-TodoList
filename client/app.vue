<template>
    <div id="app">
        <div id="cover"></div>
        <Header></Header>
        <Todo></Todo>
        <Footer></Footer>
    </div>
</template>


<script>
import Header from './layout/header.vue'
import Footer from './layout/footer.jsx'
import Todo from './views/todo/todo.vue'

export default {
    components:{
        Header,
        Footer,
        Todo
    }
}
</script>

<style lang="stylus" scoped>
#app{
    position absolute
    top 0
    bottom 0
    left 0
    right 0
}
    #cover{
        opacity 0.6
        position absolute
        top 0
        bottom 0
        left 0
        right 0
        z-index -1
    }
</style>

