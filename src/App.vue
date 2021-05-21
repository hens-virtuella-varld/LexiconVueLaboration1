<template>
  <div id="app">
    <Navbar></Navbar>
    <Hero></Hero>
    <AppFooter></AppFooter>
  </div>
</template>

<script>
import Navbar from './components/Navbar'
import Footer from './components/Footer'
import Hero from './components/Hero'
export default {
  name: 'App',
  components: {
    Navbar,
    AppFooter: Footer,
    Hero,
  }
}
</script>

<style>
</style>
