# BI0

<!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

        <!--========== BOX ICONS ==========-->
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/boxicons@latest/css/boxicons.min.css">
        <!-- <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous"> -->

        <!--========== CSS ==========-->
        <link rel="stylesheet" href="assets/css/styles.css">

        <title>My Profile</title>
    </head>
    <body >
        <!--========== HEADER ==========-->
        <header class="l-header" id="header">
            <nav class="nav bd-container">
                <a href="#Parth" class="nav__logo ">Parth</a>
               
                <div class="nav__menu" id="nav-menu">
                    <ul class="nav__list">
                        <li class="nav__item">
                            <a href="#home" class="nav__link active-link">
                                <i class='bx bxs-home nav__icon'  ></i>Home
                            </a>
                        </li> 

                        <li class="nav__item">
                            <a href="#profile" class="nav__link">
                                <i class='bx bx-user nav__icon' ></i>Profile
                        </a>
                        </li>
                        
                        <li class="nav__item">
                            <a href="#education" class="nav__link">
                                <i class='bx bx-book nav__icon'  ></i>Education
                            </a>
                        </li>
                        
                        <li class="nav__item">
                            <a href="#skills" class="nav__link">
                                <i class='bx bx-receipt nav__icon'  ></i>Skills
                            </a>
                        </li>
                        
                        <li class="nav__item">
                            <a href="#experience" class="nav__link">
                                <i class='bx bx-briefcase-alt nav__icon'  ></i>Experience
                            </a>
                        </li>
                        
                        <li class="nav__item">
                            <a href="#certificates" class="nav__link">
                                <i class='bx bx-award nav__icon'  ></i>Certificates
                            </a>
                        </li>
                        
                        <li class="nav__item">
                            <a href="#references" class="nav__link">
                                <i class='bx bx-link-external nav__icon'  ></i>References
                            </a>
                        </li>
                    </ul>
                </div>
                <div class="nav__toggle" id="nav-toggle">
                    <i class='bx bx-grid-alt'></i>
                </div>
            </nav>
        </header>

        <main class="l-main bd-container">
            <!-- All elements within this div, is generated in PDF -->
            <div class="resume" id="area-cv">
                <div class="resume__left">
                    <!--========== HOME ==========-->
                    <section class="home" id="home">
                        <div class="home__container section bd-grid">
                            <div class="home__data bd-grid">
                                <img src="assets/img/cv.JPG" alt="" class="home__img">

                                <h1 class="home__title">PARTH <b>PATEL</b></h1>
                                <h3 class="home__profession">Web developer</h3>
       
                                <!--Button to download your CV saved in the pdf folder.-->
                                <div>
                                    <a download="" href="assets/pdf/ResumeCv.pdf" class="home__button-movil">Download</a>
                                </div>
                            </div>

                            <div class="home__address bd-grid">
                                <span class="home__information">
                                    <i class='bx bx-map home__icon' ></i> Gandhinagar - Gujrat, India.
                                </span>
                                <span class="home__information">
                                    <i class='bx bx-envelope home__icon' ></i> parthkishan20@gmail.com   
                                </span>
                                <span class="home__information">
                                    <i class='bx bx-phone home__icon' ></i> +91 96620 44555
                                </span>
                            </div>
                        </div>
                        <!-- Theme change button -->
                        <i class='bx bx-moon change-theme' title="Theme" id="theme-button"></i>
    
                        <!-- Button to generate and download the pdf. Available for desktop. -->
                        <i class='bx bxs-download generate-pdf' title="Generate PDF" id="resume-button" ></i>

                    </section>          
                    
                    <!--========== SOCIAL ==========-->
                    <section class="social section">
                        <h2 class="section-title">SOCIAL</h2>

                        <div class="social__container bd-grid">
                            <a href="https://www.linkedin.com/in/parth-patel-9629751a4/" target="_blank" class="social__link">
                                <i class='bx bxl-linkedin-square social__icon' ></i> @parthkishan20
                            </a>
                            <a href="https://www.facebook.com/parthuuuu" target="_blank" class="social__link">
                                <i class='bx bxl-facebook social__icon' ></i> @parthkishan20
                            </a>
                            <a href="https://www.instagram.com/parthkishan20/" target="_blank" class="social__link">
                                <i class='bx bxl-instagram social__icon' ></i> @parthkishan20
                            </a>
                            <a href="https://twitter.com/parthkishan20" target="_blank" class="social__link">
                                <i class='bx bxl-twitter social__icon'></i> @parthkishan20
                            </a>
                        </div>
                    </section>

                    <!--========== PROFILE ==========-->
                    <section class="profile section" id="profile">
                      <h2 class="section-title">Profile</h2>  
                    
                    <p class="profile__description">Hi, there I am Parth. Currently I am doing Computer Engineering at GEC-Gandhinagar.</p>
                    </section>
                    
                    <!--========== EDUCATION ==========-->
                    <section class="education section" id="education">
                        <h2 class="section-title">Education</h2>
                    
                     <div class="education__container bd-grid">
                         <div class="education__content">
                             <div class="education__time">
                                 <span class="education__rounder"></span>
                                 <span class="education__line"></span>
                             </div>

                             <div class="education__data bd-grid">
                                 <h3 class="education__title">BECHLOR OF ENGINEERING</h3>
                                 <span class="education__studies">Computer Engineering</span>
                                 <span class="education__year">2019 - 2023</span>
                             </div>
                         </div>
                         <div class="education__content">
                            <div class="education__time">
                                <span class="education__rounder"></span>
                                <span class="education__line"></span>
                            </div>

                            <div class="education__data bd-grid">
                                <h3 class="education__title">High School</h3>
                                <span class="education__studies">Higher secondary studies, 11th & 12th Science</span>
                                <span class="education__year">2017 - 2019</span>
                            </div>
                        </div>
                        <div class="education__content">
                            <div class="education__time">
                                <span class="education__rounder"></span>
                                <!-- <span class="education__line"></span> -->
                            </div>

                            <div class="education__data bd-grid">
                                <h3 class="education__title">High School</h3>
                                <span class="education__studies">Secondary studies, 10th</span>
                                <span class="education__year">2016 - 2017</span>
                            </div>
                        </div>
                     </div>
                    </section>


                    <!--========== SKILLS  ==========-->
                    <section class="skills section" id="skills">
                       <h2 class="section-title">Skills</h2>
                       
                       <div class="skills__content bd-grid">
                           <ul class="skills_data">
                               <li class="skills__name">
                                   <span class="skills__circle"></span> Html
                               </li>
                               <li class="skills__name">
                                   <span class="skills__circle"></span> Css
                               </li>
                               <li class="skills__name">
                                   <span class="skills__circle"></span> Js 
                               </li>
                               <li class="skills__name">
                                   <span class="skills__circle"></span> Corejava
                               </li>
                               <li class="skills__name">
                                   <span class="skills__circle"></span> Python
                               </li>
                           </ul>
                           <ul class="skills_data">
                                <li class="skills__name">
                                    <span class="skills__circle"></span> Adobe Photoshop
                                </li>
                                <li class="skills__name">
                                    <span class="skills__circle"></span> Adobe Illustrator
                                </li>
                                <li class="skills__name">
                                    <span class="skills__circle"></span> Adobe Lightroom
                                </li>
                        </ul>

                       </div>
                    </section>

                </div>

                <div class="resume__right">
                    <!--========== EXPERIENCE ==========-->
                    <section class="experience section" id="experience">
                        <h2 class="section-title">Experience</h2>
                    
                    <div class="experience__container bd-grid">
                        <div class="experience__content">
                            <div class="experience__time">
                                <span class="experience__rounder"></span>
                                <span class="experience__line"></span>
                            </div>

                            <div class="experience__data bd-grid">
                                <h3 class="experience__title">MASTER OF WEBDEV</h3>
                                <span class="experience__company">Since 2020| TechBilv</span>
                                <p class="experience__description">Working as fresher here.</p>
                            </div>
                        </div>
                        <div class="experience__content">
                            <div class="experience__time">
                                <span class="experience__rounder"></span>
                               <!--<span class="experience__line"></span>--> 
                            </div>

                            <div class="experience__data bd-grid">
                                <h3 class="experience__title">MASTER OF DESIGN </h3>
                                <span class="experience__company">From 2019 to 2020 | TechBilv</span>
                                <p class="experience__description">Worked as fresher here.</p>
                            </div>
                        </div>
                       <!--
                            <div class="experience__content">
                            <div class="experience__time">
                                <span class="experience__rounder"></span>
                                 <span class="experience__line"></span> 
                            </div>

                            <div class="experience__data bd-grid">
                                <h3 class="experience__title">MASTER OF PUBG</h3>
                                <span class="experience__company">From 2018 to 2020 | KRAFTON</span>
                                <p class="experience__description">Worked as professional here.</p>
                            </div>
                        </div>                                                                         -->
                    </div>
                    </section>

                    <!--========== CERTIFICATES ==========-->
                    <section class="certificate section" id="certificates">
                        <h2 class="section-title">Certificates</h2>

                        <div class="certificate__container bd-grid">
                            <div class="certificate__content">
                                <h3 class="certificate__title">Certified for professional typing (2021)</h3>
                                <p class="certificate__description">For completing touch typing course on typing.com</p>
                            </div>

                            <div class="certificate__content">
                                <h3 class="certificate__title">Certified for completing project: responsive website (2020)</h3>
                                <p class="certificate__description">For completing responsive website project using html,css,js and bootstrap</p>
                            </div>

                            <div class="certificate__content">
                                <h3 class="certificate__title">Certified for completing designing course (2020)</h3>
                                <p class="certificate__description">For completing designing course using adobe photoshop, illustrator, lightroom, indesign from udemy/p>
                            </div>
                        </div>
                    </section>

                    <!--========== REFERENCES ==========-->
                    <section class="references section" id="references">
                        <h2 class="section-title">References</h2>

                        <div class="references__container bd-grid">
                            <div class="references__content bd-grid">
                                <span class="references__subtitle">Director | TechBilv</span>
                                <h3 class="references__title">Jay Patel</h3>
                                <ul class="references__contact">
                                    <li>Phone: +91 88665 01979</li>
                                    <li>Email: jaykumarnpatel@gmail.com</li>
                                </ul>
                            </div>

                            <div class="references__content bd-grid">
                                <span class="references__subtitle">CEO | TechBilv</span>
                                <h3 class="references__title">Rutu Patel</h3>
                                <ul class="references__contact">
                                    <li>Phone: +91 90338 78106</li>
                                    <li>Email: rutu93soni@gmail.com</li>
                                </ul>
                            </div>

                            <div class="references__content bd-grid">
                                <span class="references__subtitle">Team Leader | TechBilv</span>
                                <h3 class="references__title">Kishan Patel</h3>
                                <ul class="references__contact">
                                    <li>Phone: +91 78786 30199</li>
                                    <li>Email: parthkishan19@gmail.com</li>
                                </ul>
                            </div>
                        </div>
                    </section>

                    <!--========== LANGUAGES ==========-->
                    <section class="languages section">
                       <h2 class="section-title">Languages</h2> 
                    
                        <div class="languages__container">
                            <ul class="languages__content bd-grid">
                                <li class="languages__name">
                                    <span class="languages__circle"></span> English
                                </li>
                                <li class="languages__name">
                                    <span class="languages__circle"></span> Hindi
                                </li>
                                <li class="languages__name">
                                    <span class="languages__circle"></span> Gujrati
                                </li>
                            </ul>
                        </div>
                    </section>
                    
                    <!--========== INTERESTS ==========-->
                    <section class="interests section">
                        <h2 class="section-title">Interests</h2>
                        <div class="interests__container bd-grid">
                            <div class="interests__content">
                                <i class='bx bx-headphone interests__icon'></i>
                                <span class="interests__name">Music</span>
                            </div>
                            <div class="interests__content">
                                <i class='bx bxs-joystick interests__icon' ></i>
                                <span class="interests__name">Games</span>
                            </div>
                            <div class="interests__content">
                                <i class='bx bxs-plane-alt interests__icon' ></i>
                                <span class="interests__name">Travel</span>
                            </div>
                        
                        </div>
                    </section>

                    
                </div>
            </div>        
        </main>

        <!--========== SCROLL TOP ==========-->
        <a href="#" class="scrolltop" id="scroll-top">
            <i class='bx bx-up-arrow-alt scrolltop__icon'></i>
        </a>

        <!--========== HTML2PDF ==========-->
        <script src="assets/js/html2pdf.bundle.min.js"></script>

        <!--========== MAIN JS ==========-->
        <script src="assets/js/main.js" defer></script>
    </body>
</html>
