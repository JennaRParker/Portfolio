<template>
  <div id="nav">
    <router-link id="click" to="/">Home</router-link>
    <router-link id="click" to="/about">About</router-link>
    <router-link id="click" to="/projects">Projects and Skills</router-link>
    <router-link id="click" to="contact">Contact</router-link>
  </div>
  <router-view/>
</template>

<style>
#nav {
  font-size: 50px;
  text-align: center;
  margin-top: 4vh;
}

#click {
  margin: 30px;
  color: black;
  font-family: 'Righteous', cursive;
  background-color: white;
  border-radius: 10px;
}

</style>


