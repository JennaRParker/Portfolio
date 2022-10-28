<template>
    <div class="home">
        <div class="header">
            <div class="name-container">
                <h1 class="name">Jenna Parker</h1>
            </div>
            <div class="subtext">
                <ul>
                    <li class="sub">Based out of Atlanta, GA</li>
                    <li class="sub">Constantly learning</li>
                    <li class="sub">Let's get in touch!</li>
                </ul>
            </div>
        </div>
            <button><a href="https://github.com/">
                    <h2 class="link">GitHub</h2>
                </a></button>
            <button><a href="https://www.linkedin.com/in/jennaparkerdev/">
                    <h2 class="link">LinkedIn</h2>
                </a></button>
            <button><a
                    href="https://docs.google.com/document/d/1sBAkTLxoPMZf027ig45PKgLxRMTiTBN_6-kVZ-ybdtM/edit?usp=sharing">
                    <h2 class="link">Resume</h2>
                </a></button>
       

        <h1 class="title">About</h1>

        <h1 class="title">projects</h1>




        <h1 class="title">Skills</h1>

        <h1 class="title">Contact</h1>
    </div>
</template>

<script>

export default {
    name: 'Home',
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Righteous&display=swap');

body {
    background-color: #59253b;
}

.header {
    display: flex;
    justify-content: center;;
}

.name-container {
    width: 50vh;
}

.name {
    text-align: center;
    font-size: 15vh;
    margin: auto;
}

.subtext {
    margin: auto 5vh;
}

.sub {
    color:#0677a1;
    font-size: 4vh;
    margin: 4vh auto;
    font-family: 'Righteous', cursive;
}

h1 {
    color: white;
    font-family: 'Righteous', cursive;
}

.link {
    color: #895061;
}

button {
    background-color: white;
    border-color: #895061;
    border-width: 2vh;
    height: 10vh;
    margin: auto 2vh;
    
}
</style>