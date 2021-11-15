<template>
<SignupForm />
</template>

<script>
import SignupForm from "./components/SignupForm"

export default {
  name: 'App',
  components: { SignupForm}
}
</script>

<style>
body {
  font-family: 'Lato', sans-serif;
  font-family: 'Rubik', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  background: #f2f2f2;
}
</style>
