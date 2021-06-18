<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shivraj | Web Dev</title>
    <link rel="stylesheet" href="https://unpkg.com/flickity@2/dist/flickity.min.css">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Kristi&family=Montserrat:wght@400;500&family=Open+Sans:wght@300&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="indax.css">
    <link rel="icon" href="imgs/icon3.png">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

    <style>*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
html {
    scroll-behavior: smooth;
}
::-webkit-scrollbar {
    width: 0;
    display: none;
}
body {
    background-color: #262850;
    text-align: center;
    color: whitesmoke;
    font-family: 'Kristi', cursive;
    position: relative;
}
nav{
    padding: 0 8%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    background-color: #101834;
    height: 80px;
    width: 100%;
    font-family: 'Montserrat', sans-serif;
  }
nav ul{
    margin-right: 20px;
    float: right;
}
nav ul li{
    display: inline-block;
    margin: 0 20px;
    line-height: 80px;
}
nav ul li a{
    font-size: larger;
    text-decoration: none;
    display: block;
    color: whitesmoke;
    border: 1px solid transparent;
    transition: 0.24s ease-in-out;
}
nav ul li a:hover {
    border-bottom: 1px solid #e84545;
    color: rgb(202, 196, 255);
}
label.logo{
    float: left;
    color: white;
    font-size: 50px;
    font-family: 'Bebas Neue', cursive;
    letter-spacing: 4px;
    line-height: 80px;
    font-weight: bold;
}
.dot{
    color: #e84545;
}
.checkbtn{
    font-size: 30px;
    color: white;
    line-height: 80px;
    cursor: pointer;
    display: none;
    float: right;
}
#check{
    display: none;
}
.containar {
    background: linear-gradient(100deg, #08112be8, #313555e7);
}
.heading {
    text-align: center;
    position: relative;
    height: 100vh;
}
.nameANDline {
    position: absolute;
    top: 35%;
    left: 50%;
    transform: translate(-50%, -50%);
}
.firsth1 {
    letter-spacing: 1.5vh;
    font-size: 40px;
    text-shadow: -5px 0px 1px #000,
                3px 0px 1px #e84545,
                5px -0px 1px #000,
                -3px -0px 1px #e84545;
}
.firsth1 h1{
    font-weight: lighter;
}
.underline {
    text-decoration: underline #e84545;
    text-underline-position: under;
}
.sentence{
    letter-spacing: 1.5rem;
    font-size: 26px;
}
#chand {
    opacity: 0.8;
    position: absolute;
    right: 100px;
    top: 10px;
    width: 200px;
    height: 200px;
}
.sparkling1, .sparkling2, .sparkling3, .sparkling4, .sparkling5 {
    position: absolute;
    height: 20px;
    width: 20px;
    opacity: 0.5;
    animation-name: sparks;
    animation-duration: 1s;
    animation-iteration-count: infinite;
}
.sparkling1 {
    left: 20%;
    top: 10%;
    opacity: 0.8;
}
.sparkling2{
    left: 5%;
    top: 20%;
    opacity: 0.3;
}
.sparkling3 { 
    left: 35%;
    top: 55%;
    opacity: 0.1;
}
.sparkling4 {
    right: 35%;
    top: 10%;
    opacity: 0.4;
}
.sparkling5 {
    right: 10%;
    top: 60%;
    opacity: 0.2;
}
.stars {
    position: absolute;
    right: 30%;
    height: 50px;
    width: 50px;
    opacity: 0.7;
    animation: animate-star 25s infinite;
}
#stars2 {
    position: absolute;
    right: 20%;
    top: 5%;
    height: 30px;
    width: 30px;
    opacity: 0.3;
    animation: animate-star2 15s infinite;
}
.birds2 {
    position: absolute;
    width: 150px;
    height: 150px;
    opacity: 0.8;
    animation-name: animate-bird;
    animation-duration: 12s;
    animation-iteration-count: infinite;
}
.wave {
    position: absolute;
    right: 0;
    bottom: 0;
}
@keyframes animate-star2 {
    0% {right: 20%; top: 5%;}
    100% {right: 70%; top: 70%;}
}
@keyframes animate-star {
    0% {right: 7%; top: 17%;}
    100% {right: 60%; top: 90%;}
}
@keyframes sparks {
    0% {opacity: 0.3;}
    50% {opacity: 0.5;}
    100% {opacity: 0.8;}
}
@keyframes animate-bird {
    0% {top: 35%; left: 0%;}
    100% {
        top: 15%; 
        left: 90%;
        height: 100px;
        width: 100px;
    }
}



.page2 {
    background-color: #121b2e;
    padding: 5%;
    position: relative;
}
.sech1 h1 {
    font-size: 50px;
    font-family: 'Montserrat', sans-serif;
    line-height: 2em;
}
.page2 p {
    font-size: 25px;
    font-family: 'Open Sans', sans-serif;
}
.myphoto {
    display: flex;
    align-items: center;
    justify-content: space-around;
}
.myphoto img {
    height: 300px;
    width: 300px;
}




.page3 {
    padding: 5%;
    position: relative;
}
.edu h1{
    font-size: 50px;
    font-family: 'Montserrat', sans-serif;
}
.page3 img {
    position: absolute;
    height: 100px;
    width: 100px;
    animation: animet-page2-stars 20s infinite;
}
@keyframes animet-page2-stars {
    0% {right: 5%; top: 2%;}
    100% {right: 95%; top: 95%;}
}

.tab{
    margin: 50px auto 0 auto;
    align-content: center;
}
table {
    text-align: center;
    font-family: 'Open Sans', sans-serif;
    font-size: 25px;
    border-spacing: 100px 0px;
}
tr,td,table {
    padding: 15px;
}
.pr {
    font-size: 18px;
}



.only-photo {
    position: relative;
    margin: 5%;
}
.paper-plan {
    position: absolute;
}
.paper-plan img {
    height: 100px;
    width: 100px;
}



.page4 {
    position: relative;
    background-color: #17223b;
    padding: 5%;
    position: relative;
}
.air-baloon img {
    position: absolute;
    /* right: 10%; */
    height: 150px;
    width: 150px;
    animation: anime-air_bollon 20s infinite;
}
@keyframes anime-air_bollon {
    0% {right: 95%;}
    100% {right: 0%;}
}
.skill h1 {
    font-size: 50px;
    font-family: 'Montserrat', sans-serif;
}
table img {
    height: 30px;
    width: 30px;
}



.baloons img {
    position: absolute;
    height: 100px;
    width: 100px;
    animation: anime-bollon 20s infinite;
}
@keyframes anime-bollon {
    0% {bottom: 5%; right: 100%;}
    100% {bottom: 100%; right: 10%;}
}



.page5 {
    margin: 5%;
    position: relative;
}
.work h1 {
    margin-bottom: 30px;
    font-size: 50px;
    font-family: 'Montserrat', sans-serif;
}
.work {
    position: relative;
    margin: 0 10%;
    display: flex;
    flex-direction: column;
}
.work h2 {
    font-family: 'Open Sans', sans-serif;
    font-size: 30px;
    padding-bottom: 20px;
}
.carousel-cell {
    width: 66%;
    height: 350px;
    margin-right: 10px;
}
.carousel-cell h2 {
    font-family:monospace;
    margin: 30% 0;
    font-size: 20px;
}
.flickity-page-dots .dot {
    background-color: #060221;
}
.flickity-button {
    background: none;
    color: black;
    transition: 0.24s ease-in-out;
}
.flickity-button:hover {
    background: rgba(0, 0, 0, 0.534);
    color: white;
}
.cards {
    margin: 8% 0;
    border-radius: 10px;
}
.cards img {
    height: 350px;
    width: 80%;
    object-fit: cover;
}
.card {
    margin: 0 8%;
    border-radius: 24px;
    overflow: hidden;
}
.card img:hover {
    opacity: 0.7;
    transition: 0.24s ease-in-out;
}
.videos {
    width: 500px;
}



.footdiv {
    font-family: 'Montserrat', sans-serif;
    font-size: 20px;
    background-color: #060d22;
}
footer {
    min-height: 60vh;
    margin: 0 5% 0 5%;
    width: 90%;
    text-align: center;
}
.foot h2 {
    padding: 30px 0 30px 0;
}
.foot p {
    margin-bottom: 30px;
}
.mailid {
    margin: 20px 0 0 0;
}
.social a {
    display: inline-block;
    color: whitesmoke;
}
.social a {
    font-size: 30px;
    color: whitesmoke;
    margin: 0 3%;
}
.mailid img {
    margin-top: 10px;   
}
.social a:hover {
    transition: 0.24s;
    opacity: 0.5;
    transform: translateY(-2px);
}
.foot hr {
    width: 10%;
    border: 0;
    border-bottom: 1px solid #e84545;
    margin: 2% auto;
    text-align: center;
}
.foot .madeby p{
    font-size: small;
    font-family: 'Montserrat', sans-serif;
    margin: 0;
}
.foot .madeby .fa-heart {
    padding-bottom: 10px;
    margin: 0 3px;
    font-size: small;
}




@media screen and (max-width: 1024px) {
    .heading {
        min-height: 100vh;
    }
    .wave {
        bottom: 0%;
        height: 450px;
    }
}
@media screen and (max-width:840px) {
    nav {
        padding: 0 5%;
    }
    .heading {
        min-height: 100vh;
    }
    .birds2 {
        height: 100px;
        width: 100px;
    }
    @keyframes animate-bird {
        0% {top: 35%; left: 0%;}
        100% {
            top: 15%; 
            left: 89%;
            height: 70px;
            width: 70px;
        }
    }
    .firsth1 {
        margin-bottom: 30px;
    }
    .page2 p {
        font-size: 20px;
        line-height: 2em;
    }
    table img {
        height: 20px;
        width: 20px;
    }
    .air-baloon img {
        height: 100px;
        width: 100px;
    }
    table {
        font-size: 22px;
        border-spacing: 50px 0;
    }
    .wave {
        bottom: 0%;
        height: 350px;
    }
}
@media screen and (max-width:800px) {
    label.logo {
        float: left;
    }
    .checkbtn{
        float: right;
        display: block;
    }
    ul{
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
        z-index: 1;
        position: absolute;
        width: 100%;
        height: 100vh;
        background: linear-gradient(100deg, #060d22, #040508);
        top: 80px;
        left: -100%;
        text-align: center;
        transition: all .5s;
    }
    nav ul li{
        margin: 20px 0;
        line-height: 30px;
    }
    nav ul li a{
        display: block;
        border: 1px solid transparent;
        font-size: 20px;
    }
    nav ul li a:hover {
        border-bottom: 1px solid #e84545;
    }
    #check:checked ~ ul{
        left: 0;
    }
    .flickity-prev-next-button {
        height: 25px;
        width: 25px;
    }
}
@media screen and (max-width:700px) {
    p.aboutp, .profile, .sech1 {
        margin: 10px 0;
    }
    #chand {
        right: 5%;
        height: 150px;
        width: 150px;
    }
    .carousel-cell {
        height: 250px;
        width: 66%;
    }
    .cards img {
        height: 250px;
        width: 80%;
    }
    table {
        font-size: 20px;
        border-spacing: 20px 0;
    }
    .baloons img {
        position: absolute;
        height: 70px;
        width: 70px;
        animation: anime-bollon 20s infinite;
    }
    @keyframes anime-bollon {
        0% {bottom: 5%; right: 100%;}
        100% {bottom: 90%; right: 10%;}
    }
}
@media screen and (max-width: 500px) {
    #stars2 {
        height: 20px;
        width: 20px;
    }
    .stars{
        opacity: 0.4;
        height: 40px;
        width: 40px;
    }
    .wave {
        position: absolute;
        bottom: -8%;
        height: 400px;
        transform: scaleY(0.8);
    }
    .firsth1 {
        font-size: 30px;
    }
    .sentence {
        font-size: 22px;
        letter-spacing: 10px;
    }
    .birds2 {
        animation: animate-bird 15s infinite;
    }
    @keyframes animate-bird {
        0% {top: 35%; right: 100%;}
        100% {
            top: 15%; 
            right: 0%;
            height: 100px;
            width: 100px;
        }
    }
    .carousel-cell {
        height: 200px;
        width: 66%;
    }
    .cards img {
        height: 200px;
        width: 80%;
    }
    table {
        border-spacing: 10px 20px;
        font-size: 18px;
        padding: 10px 0;
    }
    table img {
        height: 15px;
        width: 15px;
    }
    tr,td {
        padding: 5px;
    }
    .sech1 h1 {
        font-size: 35px;
    }
    .myphoto img {
        height: 250px;
        width: 250px;
    }
    .work {
        margin: 0;
    }
    .work h1 {
        margin-bottom: 0;
    }
    .work h2 {
        font-size: 22px;
    }
    .skill h1, .work h1, .edu h1 {
        font-size: 35px;
    }
    .foot p {
        font-size: 17px;
    }
    .social .fa {
        font-size: 23px;
    }
}
@media screen and (max-width:350px) {
    .carousel-cell {
        height: 150px;
        width: 66%;
    }
    .cards img {
        height: 150px;
        width: 80%;
    }
    .birds2 {
        animation: animate-bird 15s infinite;
    }
    @keyframes animate-bird {
        0% {top: 35%; right: 100%;}
        100% {
            top: 15%; 
            right: 0%;
            height: 70px;
            width: 70px;
        }
    }
}</style>
    

    <script src="https://use.fontawesome.com/1b206dd11d.js"></script>
</head>


<body>
    <header>
        <!-- <div class="navclass"> -->
            <nav>
                <label class="logo">SR<span class="dot">.</span></label>
                <input type="checkbox" id="check">
                <label for="check" class="checkbtn"><i class="fa fa-bars" aria-hidden="true"></i></label>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About Me</a></li>
                    <li><a href="#education">Education</a></li>
                    <li><a href="#contact">Get in Touch</a></li>
                </ul>
            </nav>
        <!-- </div> -->
    </header>


    <div class="containar" id="home">
        <main>
            <div class="heading">
                <div class="moon">
                    <img id="chand" src="imgs/full-moon.png" alt="">
                </div>
                <div class="nameANDline">
                    <div class="firsth1">
                        <h1>I'm  Shivraj</h1>
                    </div>
                    <p class=sentence>A Web<span class="underline">Dev</span>loper.</p>
                </div>
                <img class="sparkling1" src="imgs/sparkling.png" alt="">
                <img class="sparkling2" src="imgs/sparkling.png" alt="">
                <img class="sparkling3" src="imgs/sparkling.png" alt="">
                <img class="sparkling4" src="imgs/sparkling.png" alt="">
                <img class="sparkling5" src="imgs/sparkling.png" alt="">
                <img class="stars" src="imgs/shooting-stars2.png" alt="">
                <img class="stars" id="stars2" src="imgs/shooting-stars2.png" alt="">
                <img class="birds2" src="imgs/birds.png" alt="">
                <img class="wave" src="imgs/wave.png" alt="">
            </div>


            <section class="page2" id="about">
                <div class="profile">
                    <div class="sech1"><h1>Ab<span class="underline">out </span>Me</h1></div>
                    <div class="myphoto"><img src="imgs/final-crop.png" alt="Photo of SR"></div>
                    <p class="aboutp"><span class="underline">Hello !</span> , I'm Shivraj Chavda <span class="underline"><b>SR</b></span>. I'm a learner from India who likes his hands on the keyboard, loves to be Creative and Camera and Photography. Maybe that's sound super cheesy :)) but yehh that's true! Currently I'm pursing 2nd year of Computer Engineering and also Working on my Web Devlopment skills as side hustle and try to get helpful output via some projects. And here you are. It's my first Portfolio on which I'm currently working.</p>
                </div>
            </section>

            <hr>

            <section class="page3" id="education">
                <div class="edu">
                    <h1>Ed<span class="underline">ucati</span>on</h1>
                    <img src="imgs/shooting-stars.png" alt="">
                    <div class="tabdiv">
                        <table class="tab">
                            <tr>
                                <td>10th</td>
                                <td>Sarvodaya Schools<br><span class="pr">88 %</span></td>
                            </tr>
                            <tr>
                                <td>12th</td>
                                <td>Dholkiya School<br><span class="pr">80 %</span></td>
                            </tr>
                            <tr>
                                <td>College</td>
                                <td>VVP Engineering College<br><span class="pr">8.62 CPI</span></td>
                            </tr>
                        </table>
                    </div>
                </div>
            </section>

            
            <div class="only-photo">
                <div class="paper-plan"><img src="imgs/paper-plane.png" alt=""></div>
            </div>
            
            <hr>
            
            <section class="page4">
                <div class="skill">
                    <h1>S<span class="underline">kill</span>s</h1>
                    <div class="air-baloon"><img src="imgs/air-balloon.png" alt=""></div>
                    <div class="skilltab">
                        <table class="tab">
                            <tr>
                                <td>Languages</td>
                                <td><img src="imgs/white1star.png" alt="stars"><img src="imgs/white1star.png" alt="stars"><img src="imgs/white1star.png" alt="stars"></td>
                            </tr>
                            <tr>
                                <td>Front-End Development</td>
                                <td><img src="imgs/white1star.png" alt="stars"><img src="imgs/white1star.png" alt="stars"><img src="imgs/white1star.png" alt="stars"></td>
                            </tr>
                            <tr>
                                <td>Photography</td>
                                <td><img src="imgs/white1star.png" alt="stars"><img src="imgs/white1star.png" alt="stars"><img src="imgs/white1star.png" alt="stars"></td>
                            </tr>
                            <tr>
                                <td>Photoshop</td>
                                <td><img src="imgs/white1star.png" alt="stars"><img src="imgs/white1star.png" alt="stars"></td>
                            </tr>
                            <tr>
                                <td>Drawing</td>
                                <td><img src="imgs/white1star.png" alt="stars"><img src="imgs/white1star.png" alt="stars"></td>
                            </tr>
                        </table>
                    </div>
                </div>
            </section>

            <hr>


            <section class="page5">
                <div class="baloons"><img src="imgs/ballons.png" alt=""></div>
                <div class="work">
                    <h1>W<span class="underline">or</span>k</h1>
                    <div class="cards photoshop">
                        <h2>Photoshop</h2>
                        <div class="carousel"
                            data-flickity='{ "wrapAround": true }'>
                            <div class="card carousel-cell">
                                <img src="imgs/ps-1-min.png" alt="">
                            </div>
                            <div class="card carousel-cell">
                                <img src="imgs/ps-3-min.png" alt="">
                            </div>
                            <div class="card carousel-cell">
                                <img src="imgs/ps-2-min.png" alt="">
                            </div>
                            <div class="card carousel-cell">
                                <img src="imgs/ps-4-min.png" alt="">
                            </div>
                            <div class="card carousel-cell">
                                <img src="imgs/ps-5-min.png" alt="">
                            </div>
                        </div>
                    </div>
                    <div class="cards photography">
                        <h2>Photography</h2>
                        <div class="carousel"
                            data-flickity='{ "wrapAround": true }'>
                            <div class="card carousel-cell">
                                <img src="imgs/photo-2-min.jpg" alt="">
                            </div>
                            <div class="card carousel-cell">
                                <img src="imgs/photo-7-min.jpg" alt="">
                            </div>
                            <div class="card carousel-cell">
                                <img src="imgs/photo-3-min.jpg" alt="">
                            </div>
                            <div class="card carousel-cell">
                                <img src="imgs/photo-6-min.jpg" alt="">
                            </div>
                            <div class="card carousel-cell">
                                <img src="imgs/photo-1-min.jpg" alt="">
                            </div>
                        </div>
                    </div>
                    <div class="cards development">
                        <h2>Front-End Project</h2>
                        <div class="carousel"
                            data-flickity='{ "wrapAround": true }'>
                            <div class="card carousel-cell fds">
                                <a href="https://codepen.io/SR_1008/pen/ZEePedQ?editors=1100"><img src="imgs/fd-1.jpg" alt=""></a>
                            </div>
                            <div class="card carousel-cell fds">
                                <a href="https://codepen.io/SR_1008/full/BaLqBPd"><img src="imgs/fd-2.jpg" alt=""></a>
                            </div>
                            <div class="card carousel-cell fds">
                                <a href="https://codepen.io/SR_1008/full/Rwpdpdy"><img src="imgs/fd-6.jpg" alt=""></a>
                            </div>
                            <div class="card carousel-cell fds">
                                <h2>Many more has to come..</h2>
                            </div>
                        </div>
                    </div>
                </div>
            </section>

            <hr>

            <div class="footdiv" id="contact">
                <footer>
                    <div class="foot">
                        <h2>Co<span class="underline">ntact </span>Me</h2>
                        <p>Here I share my Social-media links. So if you want to contact me than do so.<br>Feel free to contact me & Feedbacks are welcome.</p>
                        <div class="social">
                            <a href="https://www.linkedin.com/in/shivraj-chavda-28773b1a2"><i class="fa fa-linkedin" aria-hidden="true"></i></a>
                            <a href="https://www.facebook.com/shivraj.chavda.73/"><i class="fa fa-facebook" aria-hidden="true"></i></a>
                            <a href="https://www.instagram.com/SR_1008"><i class="fa fa-instagram" aria-hidden="true"></i></a>
                            <a href="https://codepen.io/sr_1008_/"><i class="fa fa-codepen" aria-hidden="true"></i></a>
                            <div class="mailid">
                                <a href="#"><i class="fa fa-envelope-o" aria-hidden="true"></i></a>
                                <p class="mail-font">shivrajchavda1008@gmail.com</p>
                                <hr class="last-dot">
                            </div>
                            <div class="madeby">
                                <p>made with <i class="fa fa-heart" aria-hidden="true"></i> by SR.</p>
                            </div>
                        </div>
                    </div>
                </footer>
            </div>

        </main>
    </div>
    
    <script src="https://unpkg.com/flickity@2/dist/flickity.pkgd.min.js"></script>

</body>
</html>
