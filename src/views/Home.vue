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
                <li class="sub">Let's get <a href="/contact"><span class="green">in touch</span></a></li>
            </ul>
        </div>
    </div>
    <div class="buttons">
        <button><a href="https://github.com/" target="_blank"> 
                <h2 class="link">GitHub</h2>
            </a></button>
        <button><a href="https://www.linkedin.com/in/jennaparkerdev/" target="_blank">
                <h2 class="link">LinkedIn</h2>
            </a></button>
        <button><a
                href="https://docs.google.com/document/d/1sBAkTLxoPMZf027ig45PKgLxRMTiTBN_6-kVZ-ybdtM/edit?usp=sharing" target="_blank">
                <h2 class="link">Resume</h2>
            </a></button>
    </div>
    <about />
    <projects />
    <contact />
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
    text-shadow: white 1px 0 40px;
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

button:hover {
    height: 20vh;
    width: 20vh;
    font-size: larger;
}

.buttons {
    text-align: center;
    margin-top: 10vh;
    margin-bottom: 10vh;
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

@media only screen 
and (max-device-width: 812px) {
    .name {
        font-size: 5vh;
        text-align: center;
    }
    .header {
        margin-top: 3vh;
    }
    .sub {
        font-size: 2.5vh;
        margin: 1vh
    }
    .subtext {
        margin-top: 2vh;
        text-align: left;
    }
    button {
        width: 15vh;
        height: 15vh;
        margin: 5vh;
    }
    .buttons {
        margin-top: 1vh
    }
}

</style>