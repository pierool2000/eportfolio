<script>
export default {
  name: 'Projects_Cards'
}
</script>

<template>
  <div class="project">
    <h1>Project</h1>
    <div class="sokoban">
      <h2>my_sokoban</h2>
      <p>the aim of the my_sokoban project was to remake the sokoban game in the c language using the ncurse library.</p>
    </div>
    <div class="sokoban_gameplay">
      <img src="@/assets/sokoban.gif" alt="sokoban_gameplay">
    </div>
    <div class="hunter_gameplay">
      <img src="@/assets/duck_hunt.gif" alt="hunter_gameplay">
    </div>
    <div class="hunter">
      <h3>my_hunter</h3>
      <p>the objective of the my_hunter project was to remake the game duck hunt released in 1984 on nes in csfml a library which is made in c</p>
    </div>
  </div>
</template>

<style>
.project {
  color: white;
  margin-left: 6%;
  margin-top: 1400px;
}

.project h1{
  color: white;
  font-size: 62px;
  margin-left: 1%;
  font-weight: bold;
  font-family: Ubuntu, serif;
}

.sokoban {
  border-radius: 40px;
  margin-left: 6%;
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
  height: 350px;
  width: 65%;
}

.sokoban h2 {
  font-weight: bold;
  font-family: Ubuntu, serif;
  font-size: 46px;
  margin-left: 4%;
}

.sokoban p {
  color: white;
  font-size: 38px;
  letter-spacing: 1px;
  text-align: center;
  line-height: 1.5;
  border-radius: 40px;
  margin-left: 2%;
  font-weight: bold;
  font-family: Ubuntu, serif;
}

.sokoban_gameplay {
  margin-left: 75%;
  margin-top: -350px;
  background-color: darkslategray;
  height: 340px;
  width: 340px;
  border-radius: 30px;
}

.sokoban_gameplay img {
  margin-top: 20px;
  margin-left: 20px;
  height: 300px;
  width: 300px;
}

.hunter {
  border-radius: 40px;
  margin-left: 33%;
  margin-top: -17%;
  background-color: darkslategray;
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
  height: 350px;
  width: 56%;
}

.hunter h3 {
  font-weight: bold;
  font-family: Ubuntu, serif;
  font-size: 46px;
  margin-top: 4%;
  margin-left: 4%;
}

.hunter p {
  color: white;
  font-size: 38px;
  letter-spacing: 1px;
  text-align: center;
  line-height: 1.5;
  border-radius: 40px;
  margin-left: 2%;
  font-weight: bold;
  font-family: Ubuntu, serif;
}

.hunter_gameplay {
  margin-left: 6%;
  margin-top: 150px;
  background-color: darkslategray;
  height: 340px;
  width: 540px;
  border-radius: 30px;
}

.hunter_gameplay img {
  margin-top: 20px;
  margin-left: 20px;
  height: 300px;
  width: 500px;
}
</style>