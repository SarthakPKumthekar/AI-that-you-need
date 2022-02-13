# AI-that-you-need
We ae trying to recreate Iron-Man Jarvis for your help
<!doctype html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
          content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" type="text/css" href="style.css">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.4.1/css/all.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@100;200;300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    <title>JARVIS | Home</title>
</head>
<body>
<header>
    <input type="checkbox" class="nav-toggle" id="nav-toggle">
        <div class="hamburger">
            <div class="bar"></div>
        </div>
    <img src="JARVIS.png">
    <nav class="nav">
        <ul class="nav-list">
            <li class="nav-list-element"><a onclick="document.getElementById('home').scrollIntoView(true);" class="nav-link">Home</a></li>
            <li class="nav-list-element"><a onclick="document.getElementById('about').scrollIntoView(true);" class="nav-link">About</a></li>
            <li class="nav-list-element"><a onclick="document.getElementById('download').scrollIntoView(true);" class="nav-link">Download</a></li>
            <li class="nav-list-element"><a onclick="document.getElementById('docs-contacts').scrollIntoView(true);" class="nav-link">Docs</a></li>
            <li class="nav-list-element"><a onclick="document.getElementById('docs-contacts').scrollIntoView(true);" class="nav-link">Contacts</a></li>
        </ul>
    </nav>
</header>
    <div class="hero" id="home">
        <div class="grid">
            <div class="title">
                <h1 class="convo">"Hey JARVIS!"<br>"Yes?"</h1>
                <p class="description">Meet JARVIS, your personal assistant that can not only automate tasks, but can also help you use your time more efficiently. Read more to find out.</p>
                <a onclick="document.getElementById('about').scrollIntoView(true);" class="button">Read More</a>
                <a onclick="document.getElementById('download').scrollIntoView(true);" class="button">Download</a>
            </div>
            <div class="visualiser"><img src="gif.gif" alt="" class="gif"></div>
        </div>
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
  <path fill="#f3f4f5" fill-opacity="1" d="M0,192L48,186.7C96,181,192,171,288,186.7C384,203,480,245,576,266.7C672,288,768,288,864,288C960,288,1056,288,1152,282.7C1248,277,1344,267,1392,261.3L1440,256L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"></path>
</svg>
    </div>
    <div class="about" id="about">
        <h1 class="title">'Unlike anything before'</h1>
        <p class="description">J.A.R.V.I.S is a standalone personal AI assistant that listens to your voice using Google’s Speech API and uses AI generated speech to respond to your requests. Below are some other features of JARVIS - </p>
        <p class="description">- automate tasks like opening apps, searching on browsers like Google and Firefox, opening and editing files, writing emails, telling the time, finding a location of your choice, etc. on your computer</p>
        <p class="description">
- Give daily reports of your computer usage, internet usage, app usage, amount of time sitting down and can even give recommendations based on this data. An example would be - ‘you have been sitting on your computer for over an hour, go outside and take a break!’.</p>
        <p class="description">- allows you to schedule tasks to be done at a specific time. JARVIS will even remind you of certain tasks that need completing as those deadlines approach, making sure you don’t be late for anything!</p>
    </div>
    <div class="download" id="download">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#f3f4f5" fill-opacity="1" d="M0,64L48,74.7C96,85,192,107,288,106.7C384,107,480,85,576,106.7C672,128,768,192,864,202.7C960,213,1056,171,1152,149.3C1248,128,1344,128,1392,128L1440,128L1440,0L1392,0C1344,0,1248,0,1152,0C1056,0,960,0,864,0C768,0,672,0,576,0C480,0,384,0,288,0C192,0,96,0,48,0L0,0Z"></path></svg>
        <h1 class="title">Download JARVIS</h1>
        <div class="grid">
            <div class="grid-element"><a href="" class="link"><i class="fab fa-windows"></i></a></div>
            <div class="grid-element"><a href="" class="link"><i class="fab fa-apple"></i></a></div>
            <div class="grid-element"><a href="" class="link"><i class="fab fa-linux"></i></a></div>
        </div>
    </div>
    <div class="docs-contacts" id="docs-contacts">
        <div class="grid">
            <div class="docs">
                <h1 class="title">Get Started</h1>
                <p class="description">Get started with JARVIS using our documentation. In it, we cover the basics of JARVIS - how JARVIS works, the  commands JARVIS can answer also with a simple installation process. The documentation also includes solutions to problems you might enounter with JARVIS.</p>
                <a href="https://j-a-r-v-i-s-ai.github.io/docs/" class="link">Documentation</a>
            </div>
            <div class="contacts">
                <h1 class="title">Get in Contact With Me</h1>
                <p class="description" style="float:right; width:100%;">Get in contact with us using the following links below. Mention any new features we could add to JARVIS by heading over to GitHub. Connect with me via Linkedin or email me using the button below</p>
                <ul class="social-media">
                    <li><a href="https://github.com/J-A-R-V-I-S-ai" class="social-media-link"><i class="fab fa-github"></i></a></li>
                    <li><a href="https://www.linkedin.com/in/rudra-sekhri-02162219b/" class="social-media-link"><i class="fab fa-linkedin"></i></a></li>
                    <li><a href="mailto:rudrasekhri@gmail.com" class="social-media-link"><i class="fas fa-envelope"></i></a></li>
                </ul>
            </div>
        </div>
    </div>
<div class="updates">
    <div class="grid">
        <div class="grid-element update1">
            <h1 class="title">v0.5</h1>
            <p class="description">- Be able to tell local and international time</p>
            <p class="description">- Scheduler and Timetabler capabilities. Now, JARVIS can schedule events tasks and events. JARVIS can also remind you of tasks or events that are approaching their respective deadlines.</p>
            <p class="description">- Location and Map Capabilities. Now can locate any address using Google Maps. Also responds to commands like 'search restaurants near me', etc.</p>
            <a href="" class="link">Download</a></div>
        <div class="grid-element update2">
            <h1 class="title">v0.4</h1>
            <p class="description">- Basic calc functions. Now JARVIS can add, subtract, multiply, divide, raise a number to a power, etc.</p>
            <a href="" class="link">Download</a></div>
        <div class="grid-element update3">
            <h1 class="title">v0.3</h1>
            <p class="description">- Able to get weather from any location</p>
            <a href="" class="link">Download</a></div>
        <div class="grid-element update4">
            <h1 class="title">v0.2</h1>
            <p class="description">- Revised J.A.R.V.I.S' voice and added time capabilities</p>
            <a href="" class="link">Download</a></div>
    </div>
</div>
    <div class="footer">
        <div class="grid">
            <div class="grid-element">
                <h1 class="title">About</h1>
                <p class="description">J.A.R.V.I.S is a standalone personal AI assistant that listens to your voice using Google’s Speech API and uses AI generated speech to respond to your requests.</p>
            </div>
            <div class="grid-element">
                <h1 class="title">Links</h1>
                <ul class="grid-list">
                    <li class="grid-list-element"><a onclick="document.getElementById('home').scrollIntoView(true);" class="grid-link">Home</a></li>
                    <li class="grid-list-element"><a onclick="document.getElementById('about').scrollIntoView(true);" class="grid-link">About</a></li>
                    <li class="grid-list-element"><a onclick="document.getElementById('download').scrollIntoView(true);" class="grid-link">Download</a></li>
                    <li class="grid-list-element"><a onclick="document.getElementById('docs-contacts').scrollIntoView(true);" class="grid-link">Docs</a></li>
                    <li class="grid-list-element"><a onclick="document.getElementById('docs-contacts').scrollIntoView(true);" class="grid-link">Contacts</a></li>
                </ul>
            </div>
            <div class="grid-element">
                <h1 class="title">Updates</h1>
                <div class="update">
                    <h1 class="version">v0.5</h1>
                    <h2 class="date">19 Oct</h2>
                    <p class="description">Scheduling Capabailities</p>
                </div>
                <div class="update">
                    <h1 class="version">v0.4</h1>
                    <h2 class="date">16 Oct</h2>
                    <p class="description">Can Now Close Apps</p>
                </div>
            </div>
            <div class="grid-element">
                <h1 class="title">Contacts</h1>
                <p class="description">Check out the JARVIS app on GitHub. Connect with me via Linkedin or through email</p>
                <ul class="social-media">
                    <li><a href="https://github.com/J-A-R-V-I-S-ai" class="social-media-link"><i class="fab fa-github"></i></a></li>
                    <li><a href="https://www.linkedin.com/in/rudra-sekhri-02162219b/" class="social-media-link"><i class="fab fa-linkedin"></i></a></li>
                    <li><a href="mailto:rudrathegreat@gmail.com" class="social-media-link"><i class="fas fa-envelope"></i></a></li>
                </ul>
            </div>
        </div>
        <p class="copyright">Copyright &copy; 2020. All Rights Reserved. Developed by Rudra Sekhri.</p>
    </div>
<style>
* {
    margin:0;
    padding:0;
}

html {
    scroll-behavior:smooth;
    overflow-x:hidden;
}

::-webkit-scrollbar {
    width:0px;
}

body {
    font-family:'Montserrat', sans-serif;
}

header {
    position:fixed;
    top:0;
    left:0;
    background:rgba(0,0,0,1);
    width:100%;
    height:10vh;
    z-index:5;
}

header img {
    height:5vh;
    position:fixed;
    top:2.5vh;
    left:5vw;
}

.nav {
    width:100%;
    height:100%;
}

.nav-list {
    float:right;
    display:flex;
    gap:4vw;
    height:100%;
    align-items:center;
    list-style:none;
    margin-right:10%;
}

.nav-list-element {
    padding:1vh 0vw;
    position:relative;
}

.nav-list-element:before {
    content:'';
    position:absolute;
    bottom:0;
    width:100%;
    height:2px;
    background:white;
    transform:scale(0);
    transform-origin:right;
    transition:transform 0.2s ease-in-out;
}

.nav-list-element:hover:before {
    transform:scale(1);
    transform-origin:left;
    transition:transform 0.2s ease-in-out;
}

.nav-toggle {
    position:absolute;
    top:0;
    z-index:15;
    right:0;
    margin-right:3em;
    align-items:center;
    height:100%;
    width:5vw;
    opacity:0;
    display:none;
}

.hamburger {
  height: 100%;
  position: absolute;
  top: 0%;
  right: 0;
  z-index: 14;
  display: none;
  margin-right:3em;
  justify-content: center;
  align-items: center;
  box-sizing: border-box;
  transition: all 0.3s ease-in-out;
}

.bar::before,
.bar::after,
.bar {
    width: 2em;
    height:3px;
    background:#fff;
}

.bar {
    position:relative;
    display:block;
}

.bar:before,
.bar:after {
    content:'';
    position:absolute;
    left:0;
    transition:all 0.3s ease-in-out;
}

.bar::after {
   transition:all 0.3s ease-in-out;
}

.bar::before {
    top:10px;
}

.bar::after {
    bottom:10px;
}

.nav-toggle:checked + .hamburger {
        transform: rotate(45deg);
        transform-origin:middle;
        transition:all 0.3s ease-in-out;
}

.nav-toggle:checked + .hamburger .bar::before,
.nav-toggle:checked + .hamburger .bar::after {
  top: 0;
  transform-origin:middle;
  transform: rotate(90deg);
  transition: transform 0.3s ease-in-out;
}

.nav-toggle:checked + .hamburger .bar::after {
    opacity:0;
    transition:opacity 0.3s ease-in-out;
}

.nav-toggle:checked ~ nav ul {
    display:flex;
    opacity:1;
    transform:scale(1,1);
    transform-origin:top;
    transition: opacity 0.4s ease-in-out, transform 0.2s ease-out;
}

.nav-link {
    color:#fff;
    text-decoration:none;
    font-weight:600;
    font-size:1em;
}

.hero {
    background:black;
    color:white;
    width:100%;
    min-height:100vh;
    display:flex;
    align-items:center;
    justify-content:center;
    position:relative;
}

.hero svg {
    position:absolute;
    bottom:0px;
    left:0;
}

.hero .grid {
    width:80%;
    display:grid;
    grid-template-columns:repeat(auto-fit, minmax(300px, 1fr));
    margin-top:10%;
}

.hero .title {
    margin-top:15%;
    position:relative;
    z-index:2;
}

.hero .grid h1 {
    font-size:4vw;
    font-weight:900;
}

.hero .grid p {
    font-size:1.25vw;
    line-height:1.5;
    padding-top:3vh;
    color:#bbb;
}

.hero .grid a {
    font-size:1vw;
    display:inline-block;
    padding: 1vh 2vw;
    margin-top:3vh;
    margin-right:2vw;
    background: linear-gradient(135deg, rgba(47,137,208,1) 0%, rgba(84,217,92,1) 100%);
    text-decoration:none;
    color:white;
    font-weight:600;
    text-transform:uppercase;
    transition:opacity 0.2s ease-in-out;
}

.hero .grid a:hover,
.docs-contacts a:hover {
    opacity:0.8;
    transition:opacity 0.2s ease-in-out;
}

.hero .grid img {
    width:100%;
    margin-bottom:20%;
}

.about {
    width:100%;
    min-height:100vh;
    background:#f3f4f5;
    display:flex;
    flex-direction:column;
    justify-content:center;
}

.about h1 {
    font-size:4vw;
    font-weight:900;
    color:black;
    margin-left:10%;
}

.about p {
    width:80%;
    margin-left:10%;
    padding-top:3vh;
    font-size:1.5vw;
    line-height:1.5;
    font-weight:300;
    color:#444;
}

.download {
    width:100%;
    min-height:150vh;
    background-image:url('downloads.jpg');
    background-size:cover;
    background-position:center center;
    background-repeat:no-repeat;
    position:relative;
}

.download svg {
    position:absolute;
    top:-50px;
    left:0;
}

.download .grid {
    position:absolute;
    display:flex;
    gap:10vw;
    top:110vh;
    left:50%;
    transform:translateX(-50%);
}

.download .grid-element {
    display:inline-block;
    font-size:5vw;
    color:white;
}

.download a {
    text-decoration:none;
    padding:2vh 2.5vw;
    border-radius:15px;
    transition:background 0.2s ease-in-out;
}

.download i {
    color:white;
    transition:background 0.2s ease-in;
}

.download a:hover {
    background:#f3f4f5;
    transition:background 0.2s ease-in;
}

.download a:hover > i {
    color:#222;
    transition:color 0.2s ease-in-out;
}
.download .title {
    color:white;
    font-size:4vw;
    font-weight:900;
    text-align:center;
    padding-top:30vh;
}

.docs-contacts {
    width:100%;
    min-height:100vh;
    background:#f3f4f5;
    display:flex;
    align-items:center;
    justify-content:center;
}

.docs-contacts .grid {
    width:80%;
    display:grid;
    grid-template-columns:repeat(auto-fit, minmax(300px, 1fr));
}

.docs-contacts h1 {
    font-size:4vw;
    color:black;
    font-weight:900;
}

.docs-contacts p {
    font-size:1.5vw;
    font-weight:300;
    color:#444;
    line-height:1.5;
    padding-top:3vh;
    width:90%;
    display:block;
}

.contacts {
    text-align:right;
}

.contacts .social-media {
    font-size:3vw;
    display:flex;
    gap:2vw;
    min-width:10%;
    min-height:5%;
    float:right;
    padding-top:5vh;
    list-style:none;
}

.contacts .social-media-link {
    text-decoration:none;
    color:black;
    transition:opacity 0.2s ease-in-out;
}

.docs-contacts .link {
    display:inline-block;
    margin-top:3vh;
    padding:1vh 2vw;
    text-transform:uppercase;
    color:white;
    font-weight:600;
    text-decoration:none;
    background: linear-gradient(135deg, rgba(47,137,208,1) 0%, rgba(84,217,92,1) 100%);
    transition:opacity 0.2s ease-in-out;
    font-size:1vw;
}

.footer {
    background:#111;
    width:100%;
    min-height:50vh;
    color:white;
    display:flex;
    align-items:center;
    justify-content:center;
    flex-direction:column;
}

.footer .grid {
    width:80%;
    display:grid;
    grid-template-columns:repeat(auto-fit, minmax(200px, 1fr));
    grid-column-gap:3vw;
    padding-top:10vh;
}

.footer .grid-element h1 {
    font-size:2.5vw;
    font-weight:900;
}

.footer .grid-element p {
    font-size:1.25vw;
    line-height:1.5;
    color:#bbb;
    font-weight:300;
    padding-top:1vh;
}

.footer .grid-list {
    display:flex;
    flex-direction:column;
    gap:2vh;
    list-style:none;
    margin-top:2vh;
}

.footer .grid-list a {
    text-decoration:none;
    color:#bbb;
    font-weight:600;
    transition: color 0.3s ease-in-out;
}

.grid-list a:hover {
    color:white;
    transition: color 0.3s ease-in-out;
}

.update {
    padding:1vh;
    border:2px solid white;
    border-radius:10px;
    margin-top:1vh;
    transition:background 0.2s ease-in, color 0.2s ease-in-out;
}

.update:hover {
    background:white;
    color:black;
    transition:background 0.2s ease-in, color 0.2s ease-in-out;
}

.update:hover > p {
    color:#666;
    transition:color 0.2s ease-in-out;
}

.footer .grid-element .version {
    font-size:1.5vw;
    font-weight:700;
    display:inline-block;
}

.footer .grid-element .date {
    font-size:1.5vw;
    font-weight:300;
    display:inline-block;
    float:right;
}

.footer .grid-element .update p {
    font-size:1vw;
    transition:color 0.2s ease-in-out;
}

.footer .copyright {
    padding-top:5vh;
    color:#999;
    padding-bottom:10vh;
    font-size:1vw;
}

.footer .social-media {
    font-size:2.5vw;
    display:flex;
    gap:2vw;
    min-width:10%;
    min-height:5%;
    padding-top:3vh;
    list-style:none;
}

.footer .social-media-link {
    text-decoration:none;
    color:white;
    transition:opacity 0.2s ease-in-out;
}

.updates {
    min-height:50vh;
    width:100%;
    display:flex;
    align-items:center;
    justify-content:center;
    background:#222;
    color:white;
}

.updates .grid {
    display:grid;
    padding:20vh 0;
    width:80%;
    grid-template-columns:1fr 1fr;
    grid-template-rows:1fr 1fr 1fr;
    grid-row-gap:3vh;
    grid-column-gap:3vw;
}

.updates .grid .grid-element {
    border-bottom:2px solid #f3f4f5;
    padding-bottom:3vh;
    display:flex;
    flex-direction:column;
    gap:1vh;
    justify-content:center;
    align-items:flex-start;
}

.updates .grid .grid-element p {
    font-size:1vw;
    line-height:1.5;
    color:#eee;
    font-weight:300;
}

.updates .grid-element a {
    color:white;
    display:inline-block;
    padding:1vh 2vw;
    text-transform:uppercase;
    background: linear-gradient(135deg, rgba(47,137,208,1) 0%, rgba(84,217,92,1) 100%);
    text-decoration:none;
    font-weight:600;
    font-size:1vw;
}

.updates .grid-element:not(:first-child) a {
    margin-top:2vh;
}

.updates h1 {
    font-weight:900;
    font-size:2vw;
}

.update1 {
    grid-column:1/2;
    grid-row:1/4;
    border:2px solid #f3f4f5;
    padding:3vh 3vw;
    gap:3vh !important;
}

.update2 {
    grid-column:2/3;
    grid-row:1/2;
}

.update4 {
    grid-column:2/3;
    grid-row:3/4;
}

.update3 {
    grid-column:2/3;
    grid-row:2/3;
}



@media screen and (max-width: 700px) {
    .hero .title {
        text-align:center;
    }

    .hero .grid .convo {
        font-size:6vw;
    }

    .hero .grid .description {
        font-size:2vw;
    }

    .hero .grid a {
        font-size:1.5vw !important;
    }

     .hamburger {
        display:flex;
    }

    .nav-list {
        width:100%;
        height:90vh;
        position:absolute;
        top:10vh;
        flex-direction:column;
        align-items:center;
        justify-content:center;
        background:rgba(0,0,0,0.8);
        opacity:0;
        transition: opacity 0.1s ease-in-out, transform 0.4s ease-in;
        transform-origin:top;
        z-index:-1;
        transform:scale(1,0);
    }

    .nav-toggle {
        display:block;
    }

    .about {
        text-align:center;
    }

    .about .title {
        font-size:6vw;
        margin-left:0;
    }

    .about p {
        font-size:2vw !important;
    }

    .download {
        height:100vh !important;
    }

    .download svg {
        display:none;
    }

    .download h1 {
        font-size:6vw !important;
    }

    .download a {
        font-size:10vw !important;
    }

    .docs-contacts .grid {
        grid-row-gap:10vh;
    }

    .docs-contacts .grid div {
        text-align:center !important;
        align-items:center !important;
    }

    .docs-contacts p {
        font-size:2vw !important;
        width:100%;
    }

    .docs-contacts .docs a {
        font-size:1.5vw !important;
    }

    .docs-contacts .contacts {
        display:flex;
        flex-direction:column;
        align-items:center;
        justify-content:center;
    }

    .docs-contacts .social-media {
        float:initial !important;
        padding-top:2vh;
        font-size:4vw !important;
        gap:5vw;
    }

    .docs-contacts .grid .docs h1,
    .docs-contacts .grid .contacts h1 {
        font-size:6vw;
    }

    .footer .grid {
        grid-template-columns:repeat(auto-fit, 500px);
        width:500px;
        text-align:center !important;
        grid-row-gap:5vh;
    }

    .footer .grid p {
        font-size:2vw !important;
    }

    .footer .grid h1 {
        font-size:4vw !important;
    }

    .footer .grid ul {
        font-size:2vw !important;
    }

    .footer .grid .grid-element {
        display:flex;
        flex-direction:column;
        align-items:center;
        justify-content:center;
    }

    .footer .grid .social-media {
        float:initial;
        font-size:4vw !important;
        gap:5vw;
    }

    .footer .update {
        text-align:left !important;
        width:50%;
    }

    .footer .copyright {
        font-size:1.25vw !important;
    }

    .updates h1 {
        font-size:4vw !important;
    }

    .updates p,
    .updates a {
        font-size:2vw !important
    }
}

</style>
</body>
</html>
