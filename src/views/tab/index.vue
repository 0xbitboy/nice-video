<template>
  <div>
    <div class="video-box">
      <div class="player">
         <iframe width="100%" height="100%" src='http://player.youku.com/embed/XMzIzMzg5NTUxNg==' frameborder=0 allowfullscreen ></iframe>
      </div>
      <div class="tool-bar">

      </div>
    </div>
    <div class="video-box">
      <div class="player">
         <iframe width="100%" height="100%" src='http://player.youku.com/embed/XMzIzMzg5NTUxNg==' frameborder=0 allowfullscreen ></iframe>
      </div>
      <div class="tool-bar">

      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.video-box{
  height: 180px;
}
.tool-bar{
  height: 25px;
  background: #fff;
}
</style>
