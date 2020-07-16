<template>
    <div>
         <!--=========================Home================================-->
        <section>
            <div class="landing-area">
                <div class="container">
                    <div class="landing-area-text px-4">
                        <h1 class="title is-size-3 has-text-centered is-size-4-mobile typing-anime">Rahul Sharma</h1>
                        <h2 class="title is-spaced is-size-2 has-text-centered is-size-3-mobile mr-1 font-gradient">< Front-End Web Developer /></h2>
                        <h3 class="subtitle has-text-centered has-text-weight-medium is-size-4 is-size-5-mobile has-text-black">HTML . CSS . JavaScript . NuxtJs</h3>
                        <button class="button is-dark has-text-centered btnX" role="button">Get in touch</button>
                        <button class="is-size-1 mt-2 arrow-anime btnX pointer"> <i class="fa fa-angle-down" aria-hidden="true"></i></button>
                    </div>
                </div>
            </div>
        </section>

        <!--=========================About================================-->
        <section class="section-5-2-half" id="about">
            <div class="container">
                <div class="columns is-centered  ">
                    <div class="column  is-three-fifths mb-3">
                        <img src="" alt=""  class="profile-image background-gradient"/>
                    </div>
                </div>

                <div class="columns is-centered">
                    <div class="column is-three-fifths">
                        <h1 class="title is-spaced">Hello <img src="../../assets/images/hello.png" alt="hello to everyone" class="hello-image"/></h1>
                        <h2 class="subtitle has-text-justified intro">I'm Rahul Sharma, who daily sips a <img src="../../assets/images/programming.png" style="height:1.4rem"/> cup of code, 22 years old from technical background with graduation degree <img src="../../assets/images/graduation.png" style="height:1.4rem" /> in computer science and Engineering. I'm front-end web developer and working as a freelance remotely <img src="../../assets/images/freelance.png" style="height:1.4rem" /> .</h2>
                        <h2 class="subtitle has-text-justified intro">At initial level i started creating web designs with HTML and CSS in 2018. But I not happy with that i wanted to control the whole behaviour of the body so i add JavaScript in my pocket to keep alive the body. <img src="../../assets/images/heart.png" style="height:1.4rem" /></h2>
                        <h2 class="subtitle has-text-justified intro">I always love technology and eager to learn something new so i can contribute cool stuff to open source community. In spare time i draw some paintings and reading books. <img src="../../assets/images/contribution.png" style="height:1.4rem" /></h2>
                    </div>
                </div>
            </div>
        </section>
        <hr>
         <!--=========================Services================================-->
         <section class="section-5-2-half">
                <div class="container">
                    <div class="columns is-centered">
                        <div class="column is-three-quarters has-text-centered">
                            <h1 class="title is-spaced">Make things Digital</h1>
                            <h2 class="subtitle">Digitalize the things and start creating marvelous web designs</h2>
                        </div>
                    </div>
                    <br>
                    <br>
                    <div class="columns  is-multiline is-mobile">
                            <div class="column is-12-mobile is-half-tablet is-one-third-desktop pd-2">
                                <img src="../../assets/images/code.png">
                                <h1 class="title is-size-4 is-spaced">Web Development</h1>
                                <h2 class="subtitle">HTML, CSS(BULMA), JavaScript , Nuxt.js and Express.js  we will make some cool stuff!</h2>
                            </div>
                            <div class="column is-12-mobile is-half-tablet is-one-third-desktop pd-2">
                                <img src="../../assets/images/computer.png">
                                <h1 class="title is-size-4 is-spaced">Responsive Design</h1>
                                <h2 class="subtitle">In current era we cannot show 80's unfriendly mobile website. Lets me take care of that!</h2>
                            </div>
                            <div class="column is-12-mobile is-half-tablet is-one-third-desktop pd-2">
                                <img src="../../assets/images/adobe.png">
                                <h1 class="title is-size-4 is-spaced">Adobe Illustration</h1>
                                <h2 class="subtitle">Designer who mold the ugliset shapes into attractive shapes. Lets find it and build together!</h2>
                            </div>
                           
                    </div>
                </div>
         </section>
    </div>
</template>

<style scoped>
.landing-area {
    height: 100vh;
    width:100%;
    background: url('../../assets/images/cover.jpg') no-repeat;
    background-size: cover;
    position: relative;
    /* background-image: url('../../assets/images/bg.jpg'); */
    /* background-color: #363636; */
}
.landing-area-text {
   /* background-color: #5009FF; */
   position: absolute;
   left:50%;
   top: 50%;
   transform: translate(-50%, -50%);
   width: 100%;
   max-width: 50rem;
}
.container {
    position: unset !important;
}
.typing-anime {
    animation: typing 5s steps(26), blink-caret .75s step-end infinite;
    letter-spacing: 1rem;
    white-space: nowrap;
    margin: auto;
    overflow: hidden;
    border-right: 4px solid;
    max-width: 22ch;
}
.arrow-anime {
    animation: up-down 2s ease-in-out infinite;
    background: none;
    border: 2px solid black;
    border-radius: 4px;
}
.profile-image {
    height: 13rem;
    width: 13rem;
    border-radius: 50%;
    box-shadow: 0 0 10px black;
    margin: auto;
    display: block;
}
.hello-image {
    height:2rem;
    animation: wave 2s ease-in-out;
}
.intro {
    letter-spacing: 1px;
    line-height: 1.8rem;
}
@media (max-width: 600px) {
    .typing-anime {
        letter-spacing: 0.4rem;
        max-width: 17ch;
    }
}
@Keyframes wave{
    0% {
        transform:rotate(-45deg)
    }
    40%{
        transform: rotate(0deg);
    }
    60% {
        transform: rotate(-45deg);
    }
    100% {
        transform: rotate(0deg);
    }
    
}
@Keyframes up-down {
    0% {
        opacity: 1;
    }
    50% {
        transform: translateY(1rem);
    }
    100% {
        transform: unset;
    }
}
@keyframes blink-caret {
  from, to { border-color: transparent }
  50% { border-color: #5009FF; }
}

@Keyframes typing {
    from { width: 0% }
    to { width: 26ch };
}

</style>