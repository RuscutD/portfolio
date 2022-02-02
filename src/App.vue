<template>
  <router-view/>
  <footer>
    <h2 style="margin-bottmo: 20px; color: white;">N'attendez plus, Travaillons ensemble !</h2>
      <a href="mailto:ruscuta.daavid@gmail.com" class="contact">Contactez-moi</a>
    <h2 style="font-size: 15px; margin-top: 50px;">© 2021 - Ruscuta David - Développeur et Intégrateur Web</h2>
  </footer>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

footer {
  height: 200px;
  background: black;
  padding-top: 50px;
}

.contact {
  color: white;
  font-size: 20px;
  margin-top: 50px;
}

.contact:hover {
  opacity: 70%;
}
</style>
