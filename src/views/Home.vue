<template>
    <div class="home">
        <div class="header">
            <div class="name-container">
                <h1 class="name">Jenna Parker</h1>
            </div>
        </div>
            <div class="subtext">
                <ul>
                    <li class="sub">Based out of <span class="green">Atlanta, GA</span></li>
                    <li class="sub">Constantly <span class="green">learning</span></li>
                    <li class="sub">Let's get <span class="green">in touch!</span></li>
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
                I have 5+ years of customer service experience as a brunch cook, a bartender at a retirement community,
                a sales associate at Ponce City Market and an event coordinator at a community arts center. </p>
        </div>
        <h1 class="title">Projects and Skills</h1>
        <div class="card-container">
            <a class="space" href="https://braindump-avatar.herokuapp.com/">
                <div class="card">
                    <h1 class="project-title">Brain Dump</h1>
                </div>
                <h2 class="descript">A simple, mobile platform for users to anonymously share their thoughts and comment
                    on posts.</h2>
                <div class="tech">
                    <img src=https://img.shields.io/badge/-Python-yellow />
                    <img src="https://img.shields.io/badge/-Django-yellowgreen" />
                    <img src="https://img.shields.io/badge/-PostgreSQL-blue" />
                </div>
            </a>
            <a class="space" href="https://dtoxnow.netlify.app/">
                <div class="card">
                    <h1 class="project-title">DTox</h1>
                </div>
                <h2 class="descript">Built with two other engineers to help inform users on potential toxins found in
                    every-day products.</h2>
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
                <h2 class="descript">An interactive application allowing chain-restaurant-lovers and haters to share in
                    their wisdom of fast-food experiences through the years.</h2>
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
                <h2 class="descript">A "mood ring" that retrieves a song rather than a color. Tell this application how
                    you feel or want to feel, and prepare to immerse yourself in the music of that mood.</h2>
                <div class="tech">
                    <img src="https://img.shields.io/badge/-AJAX-blue" />
                    <img src="https://img.shields.io/badge/-jQuery-red" />
                </div>
            </a>
        </div>
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
    background-color: black;

}

.header {
    justify-content: center;
    margin-top: 10vh;
}

.name {
    text-align: center;
    font-size: 20vh;
    margin: auto;
    font-family: 'Monoton', cursive;
    font-weight: 10;
    text-shadow: white 1px 0 30px;
    color: #28d536;
    
}

.subtext {
    display: flex;
    justify-content: center;
    margin-top: 7vh;
    
}

.sub {
    color: #0677a1;
    font-size: 5vh;
    margin: 4vh auto;
    font-family: 'Righteous', cursive;
    display: inline-block;
    margin: auto 6vh
}

h1 {
    color: white;
    font-family: 'Righteous', cursive;
}

.link {
    color:#0677a1;
    font-family: 'Righteous', cursive; ;
}

a {
    text-decoration: none;
}

button {
    border-color:#28d536;
    background-color:black;
    border-width: 1vh;
    height: 15vh;
    margin: auto 6vh;
    border-radius: 15vh;
    width: 15vh;
    margin: auto 10vh;
    font-size: 2vh;
    box-shadow: white 1px 0 30px; 
}

.buttons {
    text-align: center;
    margin-top: 10vh;
}

.title {
    text-align: center;
    margin-top: 15vh;
    font-size: 12vh;
    margin-bottom: 1vh;
    text-shadow: #28d536 1px 0 30px;
}

.about {
    text-align: left;
    font-size: 3vh;
    color: #0677a1;
    width: 100vh;
    margin: 12vh auto;
    font-family: 'Righteous', cursive;
}

.linked {
    color:#28d536;
    font-style: italic;
}

span {
    color:#28d536
}

.card-container {
    display: flex;
    justify-content: center;
}

.card {
    width: 50vh;
    height: 15vh;
    background-color:#0677a1;
    margin: 15vh 15vh 5vh 15vh;
    border-radius: 10vh;
    color: white;
    text-align: center;
    font-family: 'Righteous', cursive;
    display: flex;
    justify-content: center;
    box-shadow:#28d536 1px 0 30px; 
}

.project-title {
    font-size: 6vh;
}

.descript {
    text-align: center;
    width: 50vh;
    margin: auto;
    color: white;
    font-family: 'Righteous', cursive;
    font-weight: 1px;
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