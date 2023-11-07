<template>
    <nav id="navbarExample" class="navbar navbar-expand-lg fixed-top navbar-light" aria-label="Main navigation">
        <div class="container">
            <a class="navbar-brand logo-text" href="#">Ciber | Hack.py</a>
            <button class="navbar-toggler p-0 border-0" type="button" id="navbarSideCollapse"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="navbar-collapse offcanvas-collapse" id="navbarsExampleDefault">
                <ul class="navbar-nav ms-auto navbar-nav-scroll">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#header">HOME</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#ABOUT">EVENTS</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#RESOURCES">RESOURCES</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#features">RULES AND RESOURCES</a>
                    </li>
                   
                </ul>
                <span class="nav-item">
                    <a class="btn-solid-sm" href="#contact">JOIN UP</a>
                </span>
            </div>
        </div>
    </nav>
    <header id="header" class="header">
        <div class="container">
            <div class="row">
                <div class="col-lg-6 col-xl-5">
                    <div class="text-container">
                        <h1 class="h1-large">CyberQuest:CTF</h1> 
                        <p class="p-large">
𝐶𝑖𝑏𝑒𝑟 | 𝐻𝑎𝑐𝑘.𝑝𝑦 PRESENTA CyberQuest: CTF, un evento de CTF diseñado para prepararte y entrenarte con miras a participar en los eventos más importantes de hacking ético en 2024.                             
                        </p>
                        <a class="btn-solid-lg" href="#ABOUT">EVENTS</a>
                    </div>
                </div>
                <div class="col-lg-6 col-xl-7">
                    <div class="image-container">
                        <img class="img-fluid" src="assets/images/Logocyber.png" alt="alternative" width="100%" />
                    </div>
                </div>
            </div>
        </div>
          
    </header>
    <div id="ABOUT" class="cards-1 bg-gray">
        <div class="container">
            <div class="row">
                <div class="col-lg-12">
                    <h2>Entrena y participa en los eventos más destacados del hacking ético</h2>
                </div>
            </div>
            <div class="row">
                <div class="col-lg-12">
                    <div class="card">
                        <!-- <div class="card-icon green">
                            <span class="far fa-comments"></span>
                        </div> -->
                        <div class="card-body">
                            <h5 class="card-title">YUCATÁN I6 2024</h5>
                              <img class="img-fluid" src="assets/images/Yucatan6.png" alt="alternative" width="70%" />
                            <p>El “Capture The Flag Yucatán i6 2024” es un concurso dedicado a las tácticas, técnicas y procedimientos del hacking ético para la identificación y explotación de vulnerabilidades, tanto físicas como digitales. Para más información, consulta la convocatoria.</p>
                        
                        </div>
                    </div>


                    <div class="card">
                        <!-- <div class="card-icon">
                            <span class="fa-clipboard"></span>
                        </div> -->
                        <div class="card-body">
                            <h5 class="card-title">HackHowl</h5>
                              <img class="img-fluid" src="assets/images/HackHowlV2.png" alt="alternative" width="70%" />
                            <p>Evento de Captura la Bandera (CTF) y Recompensa por Bugs (Bug Bounty) organizado por la AAAIMX. Prepárate para armar tu equipo y poner a prueba tus habilidades. </p>
                           
                        </div>
                    </div>

                    <div class="card">
                        <!-- <div class="card-icon red">
                            <span class="far fa-clipboard"></span>
                        </div> -->
                        <div class="card-body">
                            <h5 class="card-title">Hackmex</h5>
                             <img class="img-fluid" src="assets/images/hackmex.png" alt="alternative" width="70%" />
                            <p>Participa en diferentes escenarios de ataque-defensa especialmente diseñados para que los participantes
puedan analizar, descubrir y explotar vulnerabilidades, ganando puntos en cada
hallazgo.</p>
                          
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </div>
     <hr class="section-divider" />
    <div id="RESOURCES" class="basic-1">
        <div class="container">
            <div class="row">
                <div class="col-lg-6 col-xl-7">
                    <div class="image-container">
                        <img class="img-fluid" src="assets/images/cyberpioct.png" alt="alternative" />
                    </div>
                </div>
                <div class="col-lg-6 col-xl-5">
                    <div class="text-container">
                        <div class="section-title">Pláticas, talleres y competencias hacking</div>
                        <h2>CyberQuest: CTF</h2>
                        <p>¡Participa en nuestro CyberQuest: CTF, penetra vulnerabilidades, hackea y prepárate con nosotros para los eventos más importantes del hacking ético!</p>
                        <a class="btn-solid-reg" href="#contact">Inscríbete</a>
                        <p>No tienes que tener experiencia!</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <hr class="section-divider" />

        <div id="features" class="container">
            <div class="row">
                <div class="col-xl-12">
                    <h2 class="h2-heading">REGLAS Y RECURSOS</h2>
                    <p class="p-heading">Revisa las reglas de nuestro evento CyberQuest: CTF para obtener más información y obten los recursos necesarios para participar</p>
                </div>
            </div>
            <div class="row">
                <div class="col-xl-12">
                    <div class="accordion" id="accordionExample">


                        <div class="accordion-item">
                            <!-- <div class="accordion-icon">
                                <span class="fas fa-tv"></span>
                            </div> -->
                            <div class="accordion-header" id="headingOne">
                                <button class="accordion-button" type="button" data-bs-toggle="collapse"
                                    data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                                   Kali Linux
                                </button>
                            </div>
                            <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne"
                                data-bs-parent="#accordionExample">
                              
                                <div class="accordion-body">Puedes descargar Kali Linux desde: <a href="https://www.kali.org/">https://www.kali.org/</a></div>

                        </div>


                        <div class="accordion-item">
                            <!-- <div class="accordion-icon blue">
                                <span class="fas fa-microphone"></span>
                            </div> -->
                            <div class="accordion-header" id="headingTwo">
                                <button class="accordion-button" type="button" data-bs-toggle="collapse"
                                    data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                                    Virtual Box
                                </button>
                            </div>
                            <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo"
                                data-bs-parent="#accordionExample">
                                <div class="accordion-body">Si deseas virtualizar Kali Linux, te recomendamos utilizar VirtualBox, que puedes encontrar en el siguiente enlace: <a href="https://www.virtualbox.org/">https://www.virtualbox.org/</a></div>

                            </div>
                        </div>


                        <div class="accordion-item">
                            <!-- <div class="accordion-icon purple">
                                <span class="fas fa-video"></span>
                            </div> -->
                            <div class="accordion-header" id="headingThree">
                                <button class="accordion-button" type="button" data-bs-toggle="collapse"
                                    data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
                                    Reglas
                                </button>
                            </div>
                            <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree"
                                data-bs-parent="#accordionExample">
                                <div class="accordion-body">Revisa las reglas con el siguiente link: <a href="https://docs.google.com/document/d/1OXAkXlavLfXSruqgv_IwdfAG2kuhxR3D/edit">Cick aqui para ver las reglas/</a></div>
                            </div>
                        </div>



                     

                    </div>
                </div>
                <!-- <div class="col-xl-7">
                    <div class="image-container">
                        <img class="img-fluid" src="assets/images/features-dashboard.png" alt="alternative" />
                    </div>
                </div> -->
            </div>
        </div>
    </div>

    <hr class="section-divider" />
    
    <div id="contact" class="basic-3">
        <div class="container">
            <div class="row">
                <div class="col-lg-12">
                    <div class="text-container">
    <h2>Inscríbete!</h2>
    <p class="p-large">¡Trae a tu equipo y los esperamos este 21 de noviembre!</p>
  <a class="btn-solid-lg" href="https://forms.gle/3Ex2K1TCHhZKUvGSA">Inscribirse</a>
</div>

                </div>
            </div>
        </div>
    </div>
     <hr class="section-divider" />
    <div class="footer bg-gray">
        <img class="decoration-circles" src="assets/images/decoration-circles.png" alt="alternative" />
        <div class="container">
            <div class="row">
                <div class="col-lg-12">
                    <h4>La seguridad no es un producto, es un proceso. 
                        - Bruce Schneier</h4>
                    <div class="social-container">
                        <span class="fa-stack">
                            <a href="#your-link">
                                <i class="fas fa-circle fa-stack-2x"></i>
                                <i class="fab fa-facebook-f fa-stack-1x"></i>
                            </a>
                        </span>
                        <span class="fa-stack">
                            <a href="#your-link">
                                <i class="fas fa-circle fa-stack-2x"></i>
                                <i class="fab fa-twitter fa-stack-1x"></i>
                            </a>
                        </span>
                        <span class="fa-stack">
                            <a href="#your-link">
                                <i class="fas fa-circle fa-stack-2x"></i>
                                <i class="fab fa-pinterest-p fa-stack-1x"></i>
                            </a>
                        </span>
                        <span class="fa-stack">
                            <a href="#your-link">
                                <i class="fas fa-circle fa-stack-2x"></i>
                                <i class="fab fa-instagram fa-stack-1x"></i>
                            </a>
                        </span>
                        <span class="fa-stack">
                            <a href="#your-link">
                                <i class="fas fa-circle fa-stack-2x"></i>
                                <i class="fab fa-youtube fa-stack-1x"></i>
                            </a>
                        </span>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="copyright bg-gray">
        <div class="container">
            <div class="row">
                <div class="col-lg-6 col-md-12 col-sm-12">
                    <ul class="list-unstyled li-space-lg p-small">
                        <li><a href="#">Article RESOURCES</a></li>
                        <li><a href="#">Terms & Conditions</a></li>
                        <li><a href="#">Privacy Policy</a></li>
                    </ul>
                </div>
                <div class="col-lg-3 col-md-12 col-sm-12">
                    <p class="p-small statement">Copyright © <a href="#">Ciber | Hack.py</a></p>
                </div>
                <div class="col-lg-3 col-md-12 col-sm-12">
                    <p class="p-small statement">Distributed by <a href="https://masukmia.com" target="_blank">Ciber | Hack.py</a></p>
                </div>
            </div>
        </div>
    </div>
    <button id="myBtn">
        <img src="assets/images/up-arrow.png" alt="alternative" />
    </button>
</template>



<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
