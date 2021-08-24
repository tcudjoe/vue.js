<template>
  <div class="container navbar">
    <Navbar/>
  </div>
  <div class="container">
    <Header color="white" h1Text="Welcome to my portfolio"/>
  </div>
  <div class="container">
    <Portfolio/>
  </div>
</template>

<script>
  import Navbar from './components/Navbar'
  import Header from './components/Header'
  import Portfolio from './components/Portfolio'

 export default {
   name: '#App',
   components: {
     Navbar,
     Header,
     Portfolio,
   }
 }
</script>
