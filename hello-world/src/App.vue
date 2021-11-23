<template>
<h1 v-bind:id="id">Hello {{ name }}</h1>
</template>

<script>

export default {
  name: 'App',
  data() {
    return {
      name: 'Nadir Bakhsh',
      id: 'heading'
    }
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

#heading {
  font-size: 4rem;
}
</style>
