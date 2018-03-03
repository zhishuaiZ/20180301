<template>
  <div class="hello">
      <index-header />
  </div>
</template>

<script>

import header from "./header.vue";

export default {
    name: 'HelloWorld',
    data () {
        return {
          counter: 0
        }
    },
    components: {
        "index-header": header
    }
}
</script>


<style scoped>

</style>
