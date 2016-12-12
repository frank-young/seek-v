<template>
  <div class="header">
    {{ msg }}
  </div>
</template>

<script>
export default {
  name: 'header',
  data () {
    return {
      msg: '这是一个标题!'
    }
  }
}
</script>

<style scoped>

</style>
