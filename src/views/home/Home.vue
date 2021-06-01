<template>
  <div class="home">
   <nav-bar class="home-nav"><div slot="center">首页</div></nav-bar>
   <main-content></main-content>
  </div>
</template>

<script>
// @ is an alias to /src
import NavBar from '@/components/common/navbar/NavBar'
import mainContent from './childComps/mainContent'

export default {
  name: 'Home',
  components: {
    NavBar,
    mainContent
  }
}
</script>
<style scoped>
 .home-nav{
   background: #1979F8;
   color:#fff;
   font-size: 18px;
   height: 44px;
 }
</style>
