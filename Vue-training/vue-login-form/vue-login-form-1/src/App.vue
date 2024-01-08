<template>
  <SignUpForm /> <!-- using the component -->
</template>

<script>
import SignUpForm from './components/SignUpForm.vue'

export default {
  name: 'App',
  components: {  SignUpForm  } // activate to use the component in html
}
</script>

<style>
#app {
  font-family: Arial, Helvetica, sans-serif;
  --webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
body {
  margin: 0;
  background: #eee;
}
</style>
