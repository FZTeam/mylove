<template>
    <div id="all">
      <myheader></myheader>
      <carecomment></carecomment>
      <tabbar></tabbar>
    </div>
</template>

<script>
  import tabbar from '../common/tabbar.vue'
  import myheader from '../common/myheader.vue'
  import carecomment from './component/carecomment.vue'
  export default {
    components:{tabbar,myheader,carecomment},
    name: 'home',
    data () {
      return {
        msg: 'care'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#all {
    padding-bottom: 1.1rem;
    padding-top: 1.4rem;
  }
</style>
