<template>
  <div style="background-color:${randomColor()};">
    <h1>Welcome to home page </h1>

  </div>
</template>

<script>
import HelloWorld from '../components/HelloWorld'

export default {
  name: 'Home',

  components: {
    HelloWorld,
  },
}
</script>
