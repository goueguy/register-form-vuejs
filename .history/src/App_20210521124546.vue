<template>
  <img alt="Vue logo" class="size" src="https://ivoiregeekschool.com/wp-content/uploads/2020/06/logo-igs2.png">
  <HelloWorld msg="BIENVENUE A IVOIRE GEEK SCHOOL"/>
  <C
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Contact from "./components/Contact";
export default {
  name: 'App',
  components: {
    HelloWorld,
    Contact
  }
}
</script>

<style>
.size{
  height: 80px;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
