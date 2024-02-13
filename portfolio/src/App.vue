<script setup xmlns="http://www.w3.org/1999/html">
import HelloWorld from "@/components/HelloWorld.vue";
import welcomeItem from "@/components/WelcomeItem.vue";
import TheWelcome from "@/components/TheWelcome.vue";
import project from "@/components/project.vue";
import contact from "@/components/contact.vue";

</script>

<template>
  <div class="page">
    <div class="back"/>
  </div>
  <welcomeItem></welcomeItem>
  <div class="box1">
    <HelloWorld></HelloWorld>
    <hr class="ligne_about">
    <TheWelcome></TheWelcome>
    <skill></skill>
    <hr class="ligne_project">
    <project></project>
    <hr class="ligne_contact">
    <contact></contact>
  </div>
</template>

<style>
.page {
  display: flex;
  text-align: center;
}

.box1 {
  flex-direction: column;
}

.back {
  z-index: -1;
  position: fixed;
  margin-top: -30px;
  height: 150%;
  width: 70px;
  margin-left: -10px;
  background-color: #100E09;
}

.ligne_about {
  z-index: -2;
  color: white;
  width: 100%;
  margin-top: 280px;
  position: absolute;
}

.ligne_project {
  z-index: -2;
  color: white;
  width: 100%;
  margin-top: 1280px;
  position: absolute;
}

.ligne_contact {
  z-index: -2;
  color: white;
  width: 100%;
  margin-top: 120px;
  position: absolute;
}
@media (max-width: 800px) {
  .ligne_about {
    margin-top: 100px;
  }
}
</style>