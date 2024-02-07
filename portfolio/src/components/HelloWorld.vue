<script>
export default {
  name: 'Projects_Cards'
}
</script>

<template>
  <div class="text">
    <h1>Pierrik Clary</h1>
    <p>epitech student</p>
  </div>
</template>

<style>

.text {
  text-align: center;
}

.text h1 {
  position: fixed;
  color: white;
  margin-top: 1px;
  font-size: 90px;
  font-weight: bold;
  font-family: Ubuntu, serif;
}

.text p {
  position: fixed;
  color: white;
  font-size: 40px;
  margin-top: 100px;
  font-weight: bold;
  font-family: Ubuntu, serif;
}

@media (max-width: 600px) {
  .text h1 {
    color: white;
    margin-top: 1px;
    font-size: 40px;
    font-weight: bold;
    font-family: Ubuntu, serif;
  }

  .text p {
    color: white;
    font-size: 20px;
    margin-top: 50px;
    font-weight: bold;
    font-family: Ubuntu, serif;
  }
}

</style>