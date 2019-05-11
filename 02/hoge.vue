<template>
  <div id="hoge">
    <p>{{ msg }}</p>
  </div>
</template>

<script>
export default {
    name: "hoge",
    data () {
        return {
            msg: 'hoge'
        }
    }
}
</script>

<style scoped>
  p {
    color: red;
  }
</style>