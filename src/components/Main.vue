<template>
  <main>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Magni totam eum obcaecati quis necessitatibus architecto voluptate, doloribus repudiandae autem. Modi eligendi debitis iusto, consectetur esse consequuntur hic quia at rem.</p>

    <Jumbotron />

    <h3>Sottotitolo</h3>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Magni totam eum obcaecati quis necessitatibus architecto voluptate, doloribus repudiandae autem. Modi eligendi debitis iusto, consectetur esse consequuntur hic quia at rem.</p>

    <Jumbotron />
  </main>
</template>

<script>
import Jumbotron from './Jumbotron.vue'

export default {
  name: 'Main',
  components: {
    Jumbotron
  }
}
</script>

<style scoped>
  p, h3{
    text-align: center;
  }
</style>