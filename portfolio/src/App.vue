<script setup>
import { ref } from 'vue'

</script>

<template>
  <div class="page">
    <div class="back">
    </div>
    <div class="title">
    </div>
  </div>
</template>

<style>
.page {
  text-align: center;
}
.title {
  margin-left: 35%;

  margin-top: 3%;
  background-color: #1520A6;
  width: 800px;
  height: 200px;
  border: 1px solid transparent;
  border-radius: 90px;
}

/*.title h1 {
  color: white;
  font-size: 100px;
  margin-top: -2px;
  text-align: center;
  font-family: 'MaPoliceWeb', sans-serif;
}

.title p {
  color: white;
  font-size: 40px;
  margin-top: -80px;
  text-align: center;
  font-family: 'MaPoliceWeb', sans-serif;
}*/

.back {
  position: fixed;
  height: 2000px;
  width: 150px;
  margin-left: -20px;
  margin-top: -5%;
  background-color: #100E09;
}

.git_logo {
  transform: scale(0.04);
  margin-top: -150px;
  margin-left: -2330PX;
}

.linkedin_logo {
  transform: scale(0.2);
  margin-top: -950px;
  margin-left: -1700PX;
}

</style>