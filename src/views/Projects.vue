<template>
    <div class="card-container">
        <div class="card">
            <h1 class="project-title">Brain Dump</h1>
            <div class="select">
                <a href="https://braindump-avatar.herokuapp.com/" target="_blank" id="deploy">Live App</a>
                <a href="https://github.com/JennaRParker/brainDump" target="_blank" id="Github">Github</a>
            </div>
            <h2 class="descript">A simple, mobile platform for users to anonymously share their thoughts and comment
                on posts.</h2>
            <div class="tech">
                <img src=https://img.shields.io/badge/-Python-yellow />
                <img src="https://img.shields.io/badge/-Django-yellowgreen" />
                <img src="https://img.shields.io/badge/-PostgreSQL-blue" />
            </div>
            <img class="proj-photo" id="brainDump"
                src="https://pbs.twimg.com/media/Fg0VgxxWABcUvm7?format=png&name=900x900">
        </div>
        <div class="card">
            <h1 class="project-title">DTox</h1>
            <div class="select">
                <a href="https://dtoxnow.netlify.app/" target="_blank" id="deploy">Live App</a>
                <a href="https://github.com/JennaRParker/DTox-Frontend" target="_blank" id="Github">Github</a>
            </div>
            <div class="outline">
                <h2 class="descript">Built with two other engineers to help inform users on potential toxins found in
                    every-day products.</h2>
                <div class="tech">
                    <img src="https://img.shields.io/badge/-React.js-blue" />
                    <img src="https://img.shields.io/badge/-Node.js-brightgreen" />
                    <img src="https://img.shields.io/badge/-Express.js-lightgrey" />
                    <img src="https://img.shields.io/badge/-Mongo.DB-orange" />
                    <img src="https://img.shields.io/badge/-Firebase-red" />
                </div>
            </div>
            <img class="proj-photo" src="https://pbs.twimg.com/media/Fg0VgysXoAAl2Jb?format=jpg&name=large">
        </div>
        <!-- </a> -->
    </div>
    <div class="card-container">
        <div class="card">
            <h1 class="project-title">Chain Reaction</h1>
            <div class="select">
                <a href="https://chain-react.herokuapp.com/" target="_blank" id="deploy">Live App</a>
                <a href="https://github.com/JennaRParker/ChainReaction" target="_blank" id="Github">Github</a>
            </div>
            <h2 class="descript">An interactive application allowing chain-restaurant-lovers and haters to share in
                their wisdom of fast-food experiences through the years.</h2>
            <div class="tech">
                <img src="https://img.shields.io/badge/-Node.js-brightgreen" />
                <img src="https://img.shields.io/badge/-Express.js-lightgrey" />
                <img src="https://img.shields.io/badge/-Mongo.DB-orange" />
            </div>
            <img class="proj-photo" src="https://pbs.twimg.com/media/Fg0VgxvXEAs83KC?format=jpg&name=large">
        </div>
        <div class="card">
            <h1 class="project-title">MOOD SING</h1>
            <div class="select">
                <a href="https://jennarparker.github.io/Mood-Sing/" target="_blank" id="deploy">Live App</a>
                <a href="https://github.com/JennaRParker/Mood-Sing" target="_blank" id="Github">Github</a>
            </div>
            <h2 class="descript">A "mood ring" that retrieves a song rather than a color. Tell this application how
                you feel or want to feel, and prepare to immerse yourself in the music of that mood.</h2>
            <div class="tech">
                <img src="https://img.shields.io/badge/-AJAX-blue" />
                <img src="https://img.shields.io/badge/-jQuery-red" />
            </div>
            <img class="proj-photo" src="https://pbs.twimg.com/media/Fg0VgxyXgAAUYoC?format=jpg&name=large">
        </div>
    </div>

    <h1 class="tools">Toolbox</h1>
    <div class="skills">
        <ul>Languages
            <li>Python</li>
            <li>JavaScript</li>
            <li>HTML5</li>
            <li>CSS3</li>
            <li>Typescript</li>
        </ul>
        <ul>Frameworks & Libraries
            <li>Vue</li>
            <li>React</li>
            <li>Django</li>
            <li>Express</li>
            <li>jQuery</li>
            <li>Bootstrap</li>
            <li>Materialize</li>
            <li>Sass</li>
        </ul>
        <ul>Databases
            <li>PostgreSQL</li>
            <li>MongoDB</li>
            <li>AWS</li>
        </ul>
        <ul>Tools
            <li>Git</li>
            <li>RESTful Routing</li>
            <li>Postman</li>
            <li>VS Code</li>
            <li>Google Firebase</li>
            <li>Windows OS</li>
            <li>Mac OS</li>
            <li>Adobe Illustrator</li>
            <li>Adobe Bridge</li>
            <li>Adobe Premiere Pro</li>
        </ul>
    </div>
</template>

<style>
.skills {
    display: flex;
    justify-content: center;
    margin-bottom: 10vh;
    box-shadow: white 1px 0 40px;
}

.tools {
    text-align: center;
    margin-top: 10vh;
    font-size: 10vh;
    text-shadow: white 1px 0 40px;
    color: #28d536;
}

ul {
    font-size: 30px;
    ;
    margin: 0 auto;
    text-align: center;
    font-family: 'Righteous', cursive;
    color: #0677a1;
}

li {
    list-style-type: none;
    font-size: 20px;
    color: #28d536;
}

.card-container {
    display: flex;
    justify-content: center;
}

.card {
    width: 50vh;
    height: 80vh;
    margin: 15vh 15vh 5vh 15vh;
    border-radius: 10vh;
    color: white;
    text-align: center;
    font-family: 'Righteous', cursive;
    justify-content: center;
}

.project-title {
    font-size: 6vh;
    text-shadow: white 1px 0 40px;
}

#brainDump {
    height: 400px;
    width: 300px;
}

.descript {
    text-align: center;
    width: 50vh;
    margin: auto;
    color: #0677a1;
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

img:hover {
    box-shadow: #28d536 1px 0 20px;
}

.proj-photo {
    width: 400px;
    height: 200px;
}

.proj-photo:hover {
    box-shadow: none;
}
</style>