<script>
export default {
  name: 'Projects_Cards'
}
</script>

<template>
    <div id="bar">
      <div class="project">
        <button>About</button>
      </div>
      <div class="description">
        <button>Project</button>
      </div>
      <div class="contact">
        <button>Contact</button>
      </div>
    </div>
    <div class="linkedin_logo">
      <a href="https://www.linkedin.com/in/pierrik-clary-837a852a1/">
        <button type="button">
          <img src="@/assets/linkedin_logo.png" alt="linkedin_logo PNG">
        </button>
      </a>
    </div>
    <div class="git_logo">
      <a href="https://github.com/pierool2000">
        <button type="button">
          <img src="@/assets/github_logo_icon_147285.png" alt="github_logoPNG">
        </button>
      </a>
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
  transform: scale(1.1);
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
  transform: scale(1.1);
}

#bar {
  position: fixed;
  margin-top: 30px;
}

#bar div {
  margin-top: 70px;
  margin-left: -95px;
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
  text-shadow: 0 0 15px rgba(255, 255, 255, 0.7);
  transform: scale(1.05);
}

@media (max-width: 600px) {
  #bar {
    position: fixed;
    margin-top: -20px;
  }

  #bar div {
    margin-top: 70px;
    margin-left: -55px;
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