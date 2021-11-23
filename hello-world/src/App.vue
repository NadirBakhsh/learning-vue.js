<template>
<h1 v-bind:class="isHeading ? 'heading' : 'text'">Hello {{ name }}</h1>

</template>

<script>

export default {
  name: 'App',
  data() {
    return {
      name: 'Nadir Bakhsh',
      id: 'heading',
      isHeading: true
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

.heading {
  font-size: 4rem;
  color: red;
}

.text {
  font-size: 1rem;
  color: blue;
}
</style>
