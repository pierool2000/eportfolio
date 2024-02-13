<script>
export default {
  name: 'Projects_Cards'
}
</script>

<template>
  <div class="text">
    <h1>HELLO</h1>
    <p>I'm Pierrik Clary</p>
  </div>
</template>

<style>

.text {
  height: 200px;
  width: 600px;
  position: absolute;
  margin-left: 40%;
}

.text h1 {
  position: absolute;
  background-color: white;
  /*background-image: linear-gradient(45deg,
  #382cbb 0%,
  #6e2088 15%,
  #374d77 25%,
  #382cbb 35%,
  #6e2088 45%,
  #374d77 55%,
  #382cbb 65%,
  #6e2088 75%,
  #374d77 85%,
  #382cbb 95%,
  #6e2088 100%);*/
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-size: 120px;
  margin-top: 0;
  margin-left: 40px;
  font-weight: bold;
  font-family: Ubuntu, serif;
}

.text p {
  position: absolute;
  background-color: white;
  /*background-image: linear-gradient(45deg,
  #382cbb 0%,
  #6e2088 15%,
  #374d77 25%,
  #382cbb 35%,
  #6e2088 45%,
  #374d77 55%,
  #382cbb 65%,
  #6e2088 75%,
  #374d77 85%,
  #382cbb 95%,
  #6e2088 100%);*/
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-size: 56px;
  font-weight: bold;
  font-family: Ubuntu, serif;
  margin-top: 140px;
  margin-left: 90px;
}

@media (max-width: 800px) {
  .text{
    margin-left: 20%;
    height: 100px;
    width: 350px;
  }

  .text h1 {
    color: white;
    margin-top: 1px;
    font-size: 55px;
    font-weight: bold;
    font-family: Ubuntu, serif;
  }

  .text p {
    color: white;
    font-size: 30px;
    margin-top: 50px;
    font-weight: bold;
    font-family: Ubuntu, serif;
    margin-left: 20px;
  }
}

</style>