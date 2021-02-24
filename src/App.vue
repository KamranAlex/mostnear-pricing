<template>
  <div class="d-flex justify-content-center">
    <img src="./assets/tm-logo.jpg" alt="" style="height:124px" />
    <h1 class="pricing-title mt-5">Pricing</h1>
  </div>
  <PricingCard />
  <Footer />
</template>

<script>
import PricingCard from './components/PricingCard'
import Footer from './components/Footer'
export default {
  name: 'App',
  components: { PricingCard, Footer },
  data() {
    return {
      title: 'Hello Vue',
    }
  },
}
</script>

<style>
#app {
  font-family: 'Rubik', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 20px;
  height: auto;
}
.pricing-title {
  color: #6f5bda;
}
</style>
