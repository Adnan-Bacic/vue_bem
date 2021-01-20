<template>
<!--
  <div class="block">
      <button class="block__elem-button button--mod-red">button</button>
      <button class="block__elem-button button--mod-blue">button</button>
      <button class="block__elem-button button--mod-green">button</button>
  </div>
  -->
  <div class="hero">
    <div class="hero__img">
      <h1 class="hero__title">Win a free vacation</h1>
      <p class="hero__subtitle">Limited time only</p>
      <button class="hero__btn btn--enter">Enter contest</button>
      <button class="hero__btn btn--terms">Terms of service</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
  //import the main file
  @import '../style/main.scss';
</style>
