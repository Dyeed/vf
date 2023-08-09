<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <br>
    <a href="/static/m.fbx" target="_blank">模型下载</a>
    <br>
    <!-- <a href="/static/plugins/x3DV/website/index.html#model=/static/m.fbx">预览</a> -->
    <!-- <iframe src="/static/plugins/x3DV/website/index.html#model=/static/m.fbx" frameborder="0">show v3dx</iframe> -->
    <iframe style="width: 100vw;" src="/static/plugins/x3DV/website/index.html#model=https://dzxx.njcit.owvlab.net/vlab_files/2022/219/0982/4gfc.fbx" frameborder="0">show v3dx</iframe>


    <br>
    <div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
