<template>
  <div id="nav">
    <router-link class="title" to="/">Home</router-link>
    <router-link class="title" to="/about">About</router-link>
    <router-link class="title" to="/projects">Projects and Skills</router-link>
    <router-link class="title" to="contact">Contact</router-link>
  </div>
  <router-view/>
</template>

<style>
#nav {
  font-size: 50px;
  text-align: center;
  margin-top: 4vh;
}

.title {
    text-align: center;
    margin: 8vh;
    font-size: 7vh;
    margin-bottom: 1vh;
    text-shadow: #79d528 10px 0 50px;
    color: white;
    font-family: 'Righteous', cursive;
}

.title:hover {
  color: #79d528;
  text-shadow: white 10px 0 50px;
}

@media only screen 
and (max-device-width: 812px) {
    .title {
      margin: 1vh;
      font-size: 1.9vh;
    }
    #nav {
      margin-top: 0;
    }
}

@media only screen 
and (min-device-width: 501px)
and (max-device-width: 1000px) {
  .title {
    margin: 2vh;
    font-size: 2.5vh
  }
}

@media only screen 
and (min-device-width: 1001px) {
  .title {
    font-size: 5vh
  }
}

@media only screen 
and (min-device-width: 200px)
and (max-device-width: 350px) {
  .title {
    font-size: 1.5vh;
    margin: 1vh
  }
}

</style>


