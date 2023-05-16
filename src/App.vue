<template>
  <div>
      <Button type="primary"  >2423432</Button>
  </div>
</template>

<script>
import {Button} from 'dodo-style/vue'

export default {
  name: 'App',
  components: {
       Button:Button
  },
    mounted() {
        console.log('Component mounted.',Button )
    }
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
</style>
