<script>
export default {
  name: 'Projects_Cards'
}
</script>

<template>
    <div id="bar">
      <div class="project">
        <button>Project</button>
      </div>
      <div class="description">
        <button>about</button>
      </div>
      <div class="contact">
        <button>contact</button>
      </div>
    </div>
    <div class="linkedin_logo">
      <button type="button">
        <img src="@/assets/linkedin_logo.png" alt="linkedin_logo PNG">
      </button>
    </div>
    <div class="git_logo">
      <button type="button">
        <img src="@/assets/github_logo_icon_147285.png" alt="github_logoPNG">
      </button>
    </div>
</template>

<style>
.linkedin_logo {
  bottom: 80px;
  position: fixed;
  width: 45px;
  height: 45px;
}

.linkedin_logo button {
  background-color: transparent;
  border-color: transparent;
  cursor: pointer;
}

.linkedin_logo button img {
  height: 45px;
}

.linkedin_logo button:hover img {
  filter: drop-shadow(0 0 10px rgba(0, 129, 255, 0.46));
}


.git_logo {
  bottom: 20px;
  position: fixed;
  background-color: transparent;
  width: 45px;
  height: 45px;
}

.git_logo button {
  margin-bottom: 90px;
  background-color: transparent;
  border-color: transparent;
  cursor: pointer;
}

.git_logo button img {
  height: 45px;
}

.git_logo button:hover img {
  filter: drop-shadow(0 0 10px rgba(255, 255, 255, 0.47));
}

#bar {
  position: fixed;
  margin-top: 70px;
}

#bar div {
  margin-top: 90px;
  margin-left: -90px;
  transform: rotate(90deg);
}

#bar div button {
  font-family: Ubuntu, serif;
  font-weight: bold;
  border-color: transparent;
  color: white;
  background-color: transparent;
  margin-bottom: 100px;
  font-size: 36px;
  cursor: pointer;
}

#bar div button:hover {
  color: #ff0000;
  text-shadow: 0 0 15px rgba(255, 255, 255, 0.7);
  transform: scale(1.05);
}

@media (max-width: 600px) {
  #bar {
    position: fixed;
    margin-top: -20px;
  }

  #bar div {
    margin-top: 90px;
    margin-left: -55px;
    transform: rotate(90deg);
  }

  #bar div button {
    font-family: Ubuntu, serif;
    font-weight: bold;
    border-color: transparent;
    color: white;
    background-color: transparent;
    margin-bottom: 50px;
    font-size: 32px;
  }
}
</style>