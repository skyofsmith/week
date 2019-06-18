
<style scoped>
  .wrapper {
    height: 100%;
    width: 100%;
  }
</style>
<template>
  <div class="wrapper">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App',
  data () {
    return {
      logo: 'https://gw.alicdn.com/tfs/TB1yopEdgoQMeJjy1XaXXcSsFXa-640-302.png'
    }
  }
}
</script>

