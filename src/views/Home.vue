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
    </div>
</template>

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
    color: #0677a1;
    font-family: 'Righteous', cursive;
    ;
}

a {
    text-decoration: none;
}

button {
    border-color: #28d536;
    background-color: black;
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
    color: #28d536;
    font-style: italic;
}

span {
    color: #28d536
}

.card-container {
    display: flex;
    justify-content: center;
}

.card {
    width: 50vh;
    height: 15vh;
    background-color: #0677a1;
    margin: 15vh 15vh 5vh 15vh;
    border-radius: 10vh;
    color: white;
    text-align: center;
    font-family: 'Righteous', cursive;
    display: flex;
    justify-content: center;
    box-shadow: #28d536 1px 0 30px;
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