
<template>
<div class="all">
<img class="profile" src="https://pbs.twimg.com/profile_images/1588947438320193536/QT_O7sk__400x400.jpg"/>


        <div class="about">
            
            <p class="chunk">
                <span class="hi">Hi! </span> My name is Jenna, and I graduated from the <a
                    href="https://generalassemb.ly/education/software-engineering-immersive" target="_blank"><span
                        class="linked">General Assembly Software
                        Engineering Immersive bootcamp</span></a> on
                10-31-22, in order to fulfill my desired pursuit to further understand the tech space and contribute to
                it in a meaningful way. </p>

            <p class="chunk"> I am a Georgia State University 2021 alumn with a Bachelor's Degree in Journalism and a
                great passion for storytelling, which I strive to bring to software engineering through
                <span>optomized user stories</span> and <span>captivating design.</span>
            </p>
            <p class="chunk">
                I have 5+ years of customer service experience as a brunch cook, a bartender at a retirement community,
                a sales associate at Ponce City Market and an event coordinator at a community arts center. I am a food-lover, a Mom to my black cat Rory, a twin, an Aunt and a life-long student. </p>
        </div>
    </div>
</template>

<style>
.hi {
    font-size: 50px;
    color: white;
}

.profile {
    width: 600px;
    height: 600px;
    margin-left: 10vh;
    margin-top: 7vh;
}

.all {
    display: flex;
}

.about {
    text-align: left;
    font-size: 3vh;
    color: #0677a1;
    width: 100vh;
    margin: 12vh auto;
    font-family: 'Righteous', cursive;
}

@media only screen 
and (max-device-width: 812px) {
    .profile {
        margin-top: 5vh;
        width: 30vh;
        height: 30vh;
    }
    .all {
        display:list-item
    }
    .about {
        width: 30vh;
        font-size: 2vh;
    }
}
</style>