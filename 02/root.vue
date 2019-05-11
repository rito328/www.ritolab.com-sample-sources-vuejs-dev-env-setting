<template>
  <div>
    <p>{{ message }}</p>
    <hoge/>
  </div>
</template>

<script>
import hoge from'./hoge'

export default {
    components: {
      hoge
    },

    data () {
        return {
            message: 'Hello, world!'
        }
    }
}
</script>

<style scoped>
  p {
    color: blue;
  }
</style>

<style>
  p {
    margin: 20px;
  }
</style>
