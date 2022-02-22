<template>
  <section class="section">
    <div class="columns is-mobile">
      <card
        title="Free"
        icon="github"
      >
        Open source on <a href="https://github.com/buefy/buefy">
          GitHub
        </a>
      </card>

      <card
        title="Responsive"
        icon="cellphone-link"
      >
        <b class="has-text-grey">
          Every
        </b> component is responsive
      </card>

      <card
        title="Modern"
        icon="alert-decagram"
      >
        Built with <a href="https://vuejs.org/">
          Vue.js
        </a> and <a href="http://bulma.io/">
          Bulma
        </a>
      </card>

      <card
        title="Lightweight"
        icon="arrange-bring-to-front"
      >
        No other internal dependency
      </card>
    </div>
    <div class="component-space">
      <div class="gazo-box">
        <square-com first-color="red" second-color="green"/><br>
        <square-com first-color="blue" second-color="yellow"/><br>
        <square-com first-color="black" second-color="purple"/><br>
        <square-com first-color="gray" second-color="white"/><br>
        <square-com first-color="lightgreen" second-color="cyan"/><br>
      </div>

      <div class="gazo-box">
        <square-com first-color="orange" second-color="purple"/><br>
        <square-com first-color="lightblue" second-color="#CEF9DC"/><br>
        <square-com first-color="cyan" second-color="purple"/><br>
        <square-com first-color="fuchsia" second-color="red"/><br>
        <square-com first-color="purple" second-color="olive"/><br>
      </div>
    </div>

  </section>
</template>

<script>
import Card from '~/components/Card'
import SquareCom from '~/components/SquareCom'

export default {
  name: 'HomePage',

  components: {
    Card,
    SquareCom,
  },

}  
</script>

<style type="text/css">
  div.gazo-box {
    float: left;
    padding-right: 200px;
    justify-content: center;
  }

  div.component-space{
    padding: 80px 150px;
  }
</style>