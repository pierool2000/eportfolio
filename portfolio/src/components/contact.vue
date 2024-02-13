<script>
export default {
  name: 'Projects_Cards'
}
</script>

<template>
  <div class="contact">
    <h1>Contact</h1>
  </div>
  <div class="email">
    <h1>email</h1>
    <div class="mail">
      <h2>pierrikclary@gmail.com</h2>
      <h3>pierrik.clary@epitech.eu</h3>
    </div>
  </div>
</template>

<style scoped>
.contact {
  margin-left: 6%;
  margin-top: 200px;
}

.contact h1 {
  color: white;
  font-size: 62px;
  margin-left: 1%;
  font-weight: bold;
  font-family: Ubuntu, serif;
}
.email {
  margin-left: 25%; 
}

.email h1 {
  font-weight: bold;
  font-family: Ubuntu, serif;
  font-size: 46px;
  margin-left: 4%;
  color: white;
}

.mail {
  border-radius: 40px;
  background-color: darkslategray;
  //background-image: linear-gradient(45deg,
  //#382cbb 0%,
  //#6e2088 15%,
  //#374d77 25%,
  //#382cbb 35%,
  //#6e2088 45%,
  //#374d77 55%,
  //#382cbb 65%,
  //#6e2088 75%,
  //#374d77 85%,
  //#382cbb 95%,
  //#6e2088 100%);
  width: 25%;
  height: 200px;
  margin-left: 5%;
}

.mail h2 {
  color: white;
  font-size: 38px;
  letter-spacing: 1px;
  text-align: center;
  line-height: 1.5;
  margin-left: 2%;
  font-weight: bold;
  font-family: Ubuntu, serif;
}

.mail h3 {
  color: white;
  font-size: 38px;
  letter-spacing: 1px;
  text-align: center;
  line-height: 1.5;
  margin-left: 2%;
  font-weight: bold;
  font-family: Ubuntu, serif;
  margin-top: 7%;
}

</style>