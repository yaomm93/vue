<template>
  <div class="hello">
    <div class="father">
      <div class="son">nihao</div>
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
  body{
    width: 100%;
    height: 100%;
  }
  .father{
    width: 100px;
    height: 100px;
    position: relative;
    background-color: antiquewhite;
  }
  .son{
    width: 50%;
    height: 50%;
    position: absolute;
    left: 0px;
    right: 0px;
    top: 0px;
    bottom: 0px;
    margin: auto;
    background-color: deeppink;
  }
</style>
