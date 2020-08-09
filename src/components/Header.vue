<template>
  <header>
    <h1>{{ title }}</h1>
  </header>
</template>

<script>
export default {
  data: () => {
    return {
      title: 'Hello World!'
    }
  }
}
</script>

<style lang="stylus" scoped>
header
  background-color lightblue
  padding 1rem
  box-shadow 0 0 5px rgba(0,0,0,.1)
  display flex
  justify-content center
  align-items center
h1
  color blanco
  margin 0
</style>
