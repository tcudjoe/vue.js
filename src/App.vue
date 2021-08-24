<template>
  <Navbar/>
  <Header textP="Hello world" color="blue" h1Text="Welcome to my portfolio"/>
</template>

<script>
  import Navbar from './components/Navbar'
  import Header from './components/Header'

 export default {
   name: '#App',
   components: {
     Navbar,
     Header,
   }
 }
</script>
