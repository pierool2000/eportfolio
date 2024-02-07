<script setup>
import HelloWorld from "@/components/HelloWorld.vue";
import welcomeItem from "@/components/WelcomeItem.vue";

</script>

<template>
  <div class="page">
    <div class="back"/>
  </div>
  <welcomeItem></welcomeItem>
</template>

<style>
.page {
  text-align: center;
}

.title {
  border: 1px solid transparent;
  border-radius: 90px;
}

.back {
  z-index: -1;
  position: fixed;
  margin-top: -10px;
  height: 100%;
  width: 70px;
  margin-left: -10px;
  background-color: #100E09;
}
</style>