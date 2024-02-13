<script>
export default {
  name: 'Projects_Cards'
}
</script>

<template>
  <div class="box">
    <div class="about">
      <h1>About</h1>
      <p>hello, my name is pierrik and i'm a student at epitech. I enrolled at epitech because code was a subject that interested me, more specifically AI, devops and video game development.
        I'm rather curious and I like to learn, I enjoy creating a lot and I'm quite creative, but my main interests are code, video games, intelligence and technology;
        in the long term I'd like to work in AI, devops or video games but if other areas such as the web and cypersecurity are subjects that interest me.</p>
    </div>
    <div class="skill">
      <h1>Skill</h1>
      <div class="logo_c">
        <button>
          <img src="@/assets/c.png" alt="logo_c">
          <p>c</p>
        </button>
      </div>
      <div class="logo_python">
        <button>
          <img src="@/assets/logo_python_fond_trnsp(1).png" alt="logo_python">
          <p>python</p>
        </button>
      </div>
      <div class="logo_html">
        <button>
          <img src="@/assets/html.png" alt="logo_html">
          <p>html</p>
        </button>
      </div>
      <div class="logo_css">
        <button>
          <img src="@/assets/css_logo.png">
          <p>css</p>
        </button>
      </div>
      <div class="logo_jetbrains">
        <button>
          <img src="@/assets/jetbrians_resize.png" alt="jetbrains_logo">
          <p>jetbrains</p>
        </button>
      </div>
      <div class="logo_godot">
        <button>
          <img src="@/assets/godot.png" alt="logo_godot">
          <p>godot</p>
        </button>
      </div>
    </div>
  </div>
</template>

<style>
.box {
  display: flex;
  flex-direction: column;
}
.about {
  margin-left: 6%;
  position: absolute;
  margin-top: 300px;
  border-radius: 40px;
  width: 60%;
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
}

.about h1 {
  color: white;
  font-size: 62px;
  margin-left: 2%;
  font-weight: bold;
  font-family: Ubuntu, serif;
}

.about p {
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

.skill {
  position: absolute;
  margin-left: 6%;
  width: 60%;
  margin-top: 850px;
}

.skill h1 {
  color: white;
  font-weight: bold;
  font-family: Ubuntu, serif;
  font-size: 62px;
  margin-left: 2%;
}

.logo_c {
  margin-left: 60px;
  position: absolute;
  height: 45px;
  width: 90px;
}

.logo_c p {
  margin-top: -8px;
  margin-left: 35px;
  font-size: 40px;
  font-family: Ubuntu, serif;
  color: gray;
}

.logo_c button {
  background-color: transparent;
  border-color: gray;
  border-radius: 40px;
  cursor: pointer;
  height: 45px;
  width: 90px;
}

.logo_c button img {
  position: absolute;
  top: 5px;
  left: 10px;
  width: 30px;
}

.logo_c button:hover {
  height: 50px;
  width: 100px;
  margin-top: -2px;
  margin-left: -2px;
}

.logo_c button:hover img {
  transform: scale(1.1);
}

.logo_c button:hover p {
  font-size: 50px;
  margin-top: -14px;
}

.logo_python {
  margin-left: 200px;
  position: absolute;
  height: 45px;
  width: 90px;
}

.logo_python p {
  margin-top: -8px;
  margin-left: 35px;
  font-size: 36px;
  font-family: Ubuntu, serif;
  color: gray;
}

.logo_python button {
  background-color: transparent;
  border-color: gray;
  border-radius: 40px;
  cursor: pointer;
  height: 45px;
  width: 180px;
}

.logo_python button img {
  position: absolute;
  top: 5px;
  left: 10px;
  width: 30px;
}

.logo_python button:hover {
  height: 50px;
  width: 200px;
  margin-top: -2px;
  margin-left: -2px;
}

.logo_python button:hover img {
  transform: scale(1.2);
  margin-top: 4px;
}

.logo_python button:hover p {
  font-size: 42px;
  margin-top: -8px;
}

.logo_html {
  margin-left: 420px;
  position: absolute;
  height: 45px;
  width: 90px;
}

.logo_html p {
  margin-top: -4px;
  margin-left: 35px;
  font-size: 36px;
  font-family: Ubuntu, serif;
  color: gray;
}

.logo_html button {
  background-color: transparent;
  border-color: gray;
  border-radius: 40px;
  cursor: pointer;
  height: 45px;
  width: 180px;
}

.logo_html button img {
  position: absolute;
  top: 5px;
  left: 10px;
  width: 30px;
  height: 30px;
}

.logo_html button:hover {
  height: 50px;
  width: 200px;
  margin-top: -2px;
  margin-left: -2px;
}

.logo_html button:hover img {
  transform: scale(1.2);
  margin-top: 4px;
}

.logo_html button:hover p {
  font-size: 42px;
  margin-top: -4px;
}

.logo_css {
  margin-left: 640px;
  position: absolute;
  height: 45px;
  width: 90px;
}

.logo_css p {
  margin-top: -4px;
  margin-left: 35px;
  font-size: 36px;
  font-family: Ubuntu, serif;
  color: gray;
}

.logo_css button {
  background-color: transparent;
  border-color: gray;
  border-radius: 40px;
  cursor: pointer;
  height: 45px;
  width: 180px;
}

.logo_css button img {
  position: absolute;
  top: 5px;
  left: 10px;
  width: 30px;
  height: 30px;
}

.logo_css button:hover {
  height: 50px;
  width: 200px;
  margin-top: -2px;
  margin-left: -2px;
}

.logo_css button:hover img {
  transform: scale(1.2);
  margin-top: 4px;
}

.logo_css button:hover p {
  font-size: 42px;
  margin-top: -4px;
}

.logo_jetbrains {
  margin-left: 280px;
  margin-top: 120px;
  position: absolute;
  height: 45px;
  width: 90px;
}

.logo_jetbrains p {
  margin-top: -4px;
  margin-left: 35px;
  font-size: 36px;
  font-family: Ubuntu, serif;
  color: gray;
}

.logo_jetbrains button {
  background-color: transparent;
  border-color: gray;
  border-radius: 40px;
  cursor: pointer;
  height: 45px;
  width: 210px;
}

.logo_jetbrains button img {
  position: absolute;
  top: 5px;
  left: 10px;
  width: 30px;
  height: 30px;
}

.logo_jetbrains button:hover {
  height: 50px;
  width: 240px;
  margin-top: -2px;
  margin-left: -2px;
}

.logo_jetbrains button:hover img {
  transform: scale(1.2);
  margin-top: 4px;
}

.logo_jetbrains button:hover p {
  font-size: 42px;
  margin-top: -4px;
}

.logo_godot {
  margin-left: 60px;
  margin-top: 120px;
  position: absolute;
  height: 45px;
  width: 90px;
}

.logo_godot p {
  margin-top: -4px;
  margin-left: 35px;
  font-size: 36px;
  font-family: Ubuntu, serif;
  color: gray;
}

.logo_godot button {
  background-color: transparent;
  border-color: gray;
  border-radius: 40px;
  cursor: pointer;
  height: 45px;
  width: 180px;
}

.logo_godot button img {
  position: absolute;
  top: 5px;
  left: 10px;
  width: 30px;
  height: 30px;
}

.logo_godot button:hover {
  height: 50px;
  width: 200px;
  margin-top: -2px;
  margin-left: -2px;
}

.logo_godot button:hover img {
  transform: scale(1.2);
  margin-top: 4px;
}

.logo_godot button:hover p {
  font-size: 42px;
  margin-top: -4px;
}

@media (max-width: 800px) {
  .about {
    margin-top: 150px;
    margin-left: 15%;
    width: 80%;
  }

  .about h1 {
    margin-left: 15px;
  }

  .about p {
    font-size: 26px;
  }
}


</style>