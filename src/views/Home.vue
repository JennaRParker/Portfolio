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
        <div class="buttons">
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
        </div>

        <h1 class="title">About</h1>
        <div class="about">
            <p class="chunk">
                Hi! My name is Jenna, and I graduated from the <a
                    href="https://generalassemb.ly/education/software-engineering-immersive"><span
                        class="linked">General Assembly Software
                        Engineering Immersive</span></a> on
                10-31-22, in order to fulfill my desired persuit to further understand the tech space and contribute to
                it in a meaningful way. </p>

            <p class="chunk"> I am a Georgia State University 2021 alumn with a Bachelor's Degree in Journalism and a
                great passion for storytelling which I strive to bring software engineering through clear, intentionally
                <span>optomized user stories</span> and <span>captivating design.</span>
            </p>
            <p class="chunk">
                I have 5+ years of costumer service experience as a brunch cook, a bartender at a retirement community,
                a sales associate at Ponce City Market and an event coordinator at a community arts center. </p>
        </div>
        <h1 class="title">Projects and Skills</h1>
        <div class="card-container">
            <a href="https://braindump-avatar.herokuapp.com/">
                <div class="card">
                <h1 class="project-title">Brain Dump</h1>
                </div>
                <div class="tech">
                <img src=https://img.shields.io/badge/-Python-yellow />
                <img src="https://img.shields.io/badge/-Django-yellowgreen" />
                <img src="https://img.shields.io/badge/-PostgreSQL-blue" />
            </div>
        </a>
            <a href="https://dtoxnow.netlify.app/">
                <div class="card">
                    <h1 class="project-title">DTox</h1>
                </div>
                <div class="tech">
                <img src="https://img.shields.io/badge/-React.js-blue" />
                <img src="https://img.shields.io/badge/-Node.js-brightgreen" />
                <img src="https://img.shields.io/badge/-Express.js-lightgrey" />
                <img src="https://img.shields.io/badge/-Mongo.DB-orange" />
                <img src="https://img.shields.io/badge/-Firebase-red" />
                </div>
            </a>
        </div>
        <div class="card-container">
            <a href="https://chain-react.herokuapp.com/">
                <div class="card">
                    <h1 class="project-title">Chain Reaction</h1>
                </div>
                <div class="tech">
                <img src="https://img.shields.io/badge/-Node.js-brightgreen" />
                <img src="https://img.shields.io/badge/-Express.js-lightgrey" />
                <img src="https://img.shields.io/badge/-Mongo.DB-orange" />
                </div>
            </a>
            <a href="https://jennarparker.github.io/Mood-Sing/">
                <div class="card">
                    <h1 class="project-title">Mood Sing</h1>
                </div>
                <div class="tech">
                <img src="https://img.shields.io/badge/-AJAX-blue" />
                <img src="https://img.shields.io/badge/-jQuery-red" />
                </div>
            </a>
        </div>

        <h1 class="title">Contact</h1>
    </div>
</template>

<script>

export default {
    name: 'Home',
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Monoton&family=Righteous&display=swap');

body {
    background-color: #59253b;

}

.header {
    display: flex;
    justify-content: center;
    margin-top: 10vh
}

.name-container {
    width: 50vh;
}

.name {
    text-align: left;
    font-size: 11vh;
    margin: auto;
    font-family: 'Monoton', cursive;
    font-weight: 10;
}

.subtext {
    margin: auto 5vh;
}

.sub {
    color: #0677a1;
    font-size: 4vh;
    margin: 4vh auto;
    font-family: 'Righteous', cursive;
}

h1 {
    color: white;
    font-family: 'Righteous', cursive;
}

.link {
    color: white;
}

button {
    border-color: white;
    background-color: #0677a1;
    border-width: 1vh;
    height: 10vh;
    margin: auto 6vh;
    border-radius: 15vh;
    width: 15vh
}

.buttons {
    text-align: center;
    margin-top: 5vh;
}

.title {
    text-align: center;
    margin-top: 15vh;
    font-size: 12vh;
    margin-bottom: 1vh
}

.about {
    text-align: left;
    font-size: 3vh;
    color: #895061;
    width: 100vh;
    margin: auto;
    font-family: 'Righteous', cursive;
}

.linked {
    color: white;
}

span {
    color: #0677a1;
}

.card-container {
    display: flex;
    justify-content: center;
}

.card {
    width: 50vh;
    height: 15vh;
    background-color: #895061;
    margin: 15vh 15vh 5vh 15vh;
    border-radius: 10vh;
    color: white;
    text-align: center;
    font-family: 'Righteous', cursive;
    display: flex;
    justify-content: center;
}

.project-title {
    font-size: 6vh;
}

.tech {
    margin-top: 0;
    width: 50vh;
    text-align: center;
    margin: auto;
}

img {
    width: 90px;
    height: 50px;
    margin: 10px;
}
</style>