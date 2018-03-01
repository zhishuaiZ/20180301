<template>
  <div class="hello">
      {{msg}}
  </div>
</template>

<script>


export default {
  data () {
    return {
      msg: 'header'
    }
  }
}
</script>


<style scoped>
    .hello{
        background: red;
    }
</style>
