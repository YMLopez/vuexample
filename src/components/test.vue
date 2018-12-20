<template>

  <div id='content'>
    世界如此美妙，我却如此烦躁。<br>
    {{msg}}
  </div>

</template>

<script>
export default {
  name: 'test',
  data () {
    return {
      msg: 'not just saying.'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#content{
  margin-top: 30px;
}
</style>
