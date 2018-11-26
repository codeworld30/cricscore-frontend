<template>
    <div id="app">
        <Header/>
        <Footer/>
    </div>
</template>

<script>
import Header from './components/Header/Header'
import Footer from './components/Footer/Footer'

export default {
  name: 'app',
  components: {
      Footer,
      Header,
  }
}
</script>

<style lang="scss" scoped>

</style>
