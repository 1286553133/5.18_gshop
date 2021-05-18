<template>
  <div>
    <router-view></router-view>
    <FooterGuide v-if="$route.meta.showFooter"></FooterGuide>
  </div>
</template>
<style lang="stylus"></style>
<script>
import FooterGuide from './components/FootGuide/FootGuide'
export default {

  components: {

    FooterGuide
  }
}
</script>
