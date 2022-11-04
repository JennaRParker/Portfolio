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
    text-shadow: #28d536 10px 0 50px;
    color: white;
    font-family: 'Righteous', cursive;
}

</style>


