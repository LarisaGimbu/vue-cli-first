<template>
  <div>
    <section class="jumbotron">
        <div class="jumbo-text">
          <p class="jumbo-title"> Pretium placerat diu interdum nunc in eros urna morbi</p>
          <p class="jumbo-subtitle"> Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi facere voluptas minus, aspernatur alias error ab in eligendi</p>
        </div>
      </section>
  </div>
</template>

<script>
export default {
  name: 'Jumbotron'
}
</script>

<style scoped>
  .jumbotron{
  height: 400px;
  background-color: bisque;
  margin-bottom: 20px;
  border-radius: 7px;
}

.jumbo-text{
  height: 100%; 
  border-radius: 7px;
  padding: 20% 0 10% 40px;
}

.jumbotron p{
  width: 60%;
  color: chocolate;
}

.jumbo-title{
  font-size: 30px;
}

.jumbo-subtitle{
  font-size: 15px;
}

.jumbo-subtitle::after{
  content: '...';
}
</style>