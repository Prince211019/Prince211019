
<html lang="en">

    <head>

        <meta charset="UTF-8">

        <meta http-equiv="X-UA-Compatable" content="IE-edge">

        <meta name="viewport" content="width-device-width, initial-scale=1.0">

        <title>PERSONAL PORTFOLIO WEBSITE</title>

        <link rel="stylesheet" href="style.css">

        <script src="https://kit.fontawesome.com/yourcode.js" crossorigin="anonymous"></script>

    </head>

    <body>

        <div id="header">

            <div class="container">

                <nav>

                    <img src="images/logo.png" class="logo">

                    <ul id="sidemenu">

                        <li><a href="#header">Home</a></li>

                        <li><a href="#about">About</a></li>

                        <li><a href="#projects">Projects</a></li>

                        <li><a href="#contact">Contact</a></li>

                        <i class="fas fa-times" onclick="closemenu()"></i>

                    </ul>

                    <i class="fas fa-times"onclick="openmenu()"></i>

                </nav>

                <div class="header-text">

                    <p>codeclause webdeveloment project-1</p>

                    <h1>Hi,I'm<span> uma </span>from IIIT</h1>

                </div>

            </div>

        </div>

<!-----------------about------------------->

        <div id="about">

            <div class="container">

                <div class="row">

                    <div class="about-col-1">

                        <img src="images/user.jpg">

                    </div>

                        <div class="about-col-2">

                            <h1 class="sub-title">About Me</h1>

                            <p>im uma im from srikalahasthi chittoor dist currently im persuing my btech 3rd year in the department of cse from rgukt rkvalley ,it is a webdeveloment project assigned to me by codeclause ,it is a personal portfolio website.

                            </p>

                            <div class="tab-titles">

                                <p class="tab-links active-link" onclick="opentab('Skills')">Skills</p>

                                <p class="tab-links" onclick="opentab('Hobbies')">Hobbies</p>

                                <p class="tab-links" onclick="opentab('Education')">Education</p>

                            </div>

                            <div class="tab-contents active-tab" id="Skills">

                                <ul>

                                    <li><span>webdeveloment</span><br>Designing</li>

                                    <li><span>java </span><br>programming</li>

                                    <li><span>python</span><br>programming</li>

                                </ul>

                            </div>

                            <div class="tab-contents" id="Hobbies">

                                <ul>

                                    <li><span>Listening</span>Music</li>

                                    <li><span>Reading</span>Books</li>

                                    <li><span>Drawing</span>pictures</li>

                                </ul>

                            </div>

                            <div class="tab-contents" id="Education">

                                <ul>

                                    <li><span>10TH-STANDARD</span>ZPGHS IN SRIKALAHASTHI WITH 10CGPA</li>

                                    <li><span>PUC</span>IIIT RGUKT RKVALLEY IDUPULAPAYA</li>

                                    <li><span>Btech-CSE</span>IIIT RGUKT RKVALLEY IDUPULAPAYA</li>

                                </ul>

                            </div>

                        </div>

                </div>Skills

            </div>

        </div>

        <!------------------projects-------------------->

        <div id="projects">

            <div class="container">

                <h1 class="sub-title">My Projects</h1>

                <div class="projects-list">

                    <div>

                        <i class="fas fa-code"></i>

                        <h2>DEVOTIONAL TOURISM</h2>

                        <p>It is a team porject done by three members and in this project i played a role as frontend developer and databases.,This project guides peoples for devotional places and easy to find out where it was and also in this website we are providing traveling facilities also .</p>            

                        <a href="#">learn more</a>

                    </div>

                    <div>

                        <i class="fas fa-crop-alt"></i>

                        <h2>Landing Page</h2>

                        <p>It is a team porject done by three members and in this project i played a role as frontend developer and databases.,It is a standalone web page ,created specifically for a marketing or advertising.</p>            

                        <a href="#">learn more</a>

                    </div>

                    <div>

                        <i class="fab fa-app-store"></i>

                        <h2>Background Generator</h2>

                        <p>It is a team porject done by three members and in this project i played a role as frontend developer.In this project we can change the background color whenever we want.it appears like multicolored we can change the colors left and right sides.</p>            

                        <a href="#">learn more</a>

                    </div>

                </div>

            </div>

        

        </div>

        <!-----------contact----------->

        <div id="contact">

            <div class="container">

                <div class="row">

                    <div class="contact-left">

                        <h1 class=""sub-title">Contact me</h1>

                        <p>example@gmail.com</p>

                        <p> 0123456789</p>

                        <div class="social-icons">

                            <a href="https://facebook.com"><i class="fan fa-facebook"></i></a>

                            <a href=""><i class="fan fa-instagram"></i></a>

                        </div>

            

                    </div>

                </div>

            </div>

           

        </div>

        <script>

            var tablinks = document.getElementsByClassName("tab-links");

            var tabcontents = document.getElementsByClassName("tab-contents");

            function opentab(tabname){

                for(tablink of tablinks){

                    tablink.classList.remove("active-link");

                }

                for(tabcontent of tabcontents){

                    tabcontent.classList.remove("active-tab");

                }

                event.currentTarget.classList.add("active-link");

                document.getElementById(tabname).classList.add("active-tab"); 

            }

        </script>

        <script>

            var sidemenu = deocument.getElementById("sidemenu");

            function openmenu(){

                sidemenu.style.right = "0";

            }

            function closemenu(){

                sidemenu.style.right = "-200px";

            }

        </script>

        

    </body>

</html>
