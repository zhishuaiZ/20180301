<template>
  <div class="hello">
      <index-header />
      {{msg}}
  </div>
</template>

<script>

import header from "./header.vue";

export default {
    name: 'HelloWorld',
    data () {
        return {
          msg: 'Welcome to Your Vue.js App'
        }
    },
    components: {
        "index-header": header
    }

}
</script>


<style scoped>

</style>
