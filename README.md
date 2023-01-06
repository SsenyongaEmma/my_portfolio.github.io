# my-portfolio
A web-App best portfolio built with html, css, javascript, bootsrap, python and django 
<html>
  <body>
    <h3>Hello World!</h3>
    <a href="https://ssenyongaemma.github.io/my_portfolio.github.io/index.html">click here to visit the portfolio...</a>
  </body>
  </html>
  {% load static %}

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta content="width=device-width, initial-scale=1.0" name="viewport">

  <title>portfolio</title>
  <meta content="" name="description">
  <meta content="" name="keywords">

  <!-- Favicons -->
  <link href="{% static 'assets/img/emma_dante.jpg' %}" rel="icon">
  <link href="assets/img/apple-touch-icon.png" rel="apple-touch-icon">

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css?family=Open+Sans:300,300i,400,400i,600,600i,700,700i|Raleway:300,300i,400,400i,500,500i,600,600i,700,700i|Poppins:300,300i,400,400i,500,500i,600,600i,700,700i" rel="stylesheet">

  <!-- Vendor CSS Files -->
  <link href="{% static 'assets/vendor/aos/aos.css' %}" rel="stylesheet">
  <link href="{% static 'assets/vendor/bootstrap/css/bootstrap.min.css' %}" rel="stylesheet">
  <link href="{% static 'assets/vendor/bootstrap-icons/bootstrap-icons.css' %}" rel="stylesheet">
  <link href="{% static 'assets/vendor/boxicons/css/boxicons.min.css' %}" rel="stylesheet">
  <link href="{% static 'assets/vendor/glightbox/css/glightbox.min.css' %}" rel="stylesheet">
  <link href="{% static 'assets/vendor/swiper/swiper-bundle.min.css' %}" rel="stylesheet">

  <!-- Template Main CSS File -->
  <link href="{% static 'assets/css/style.css' %}" rel="stylesheet">

  <!-- =======================================================
  * Template Name: iPortfolio - v3.9.1
  * Template URL: https://bootstrapmade.com/iportfolio-bootstrap-portfolio-websites-template/
  * Author: BootstrapMade.com
  * License: https://bootstrapmade.com/license/
  ======================================================== -->
</head>

<body>

  <!-- ======= Mobile nav toggle button ======= -->
  <i class="bi bi-list mobile-nav-toggle d-xl-none"></i>

  <!-- ======= Header ======= -->
  <header id="header">
    <div class="d-flex flex-column">

      <div class="profile">
        <img src="{% static 'assets/img/emma_dante.jpg' %}" alt="" class="img-fluid rounded-circle">
        <h1 class="text-light"><a href="index.html">Ssenyonga Emma</a></h1>
        <div class="social-links mt-3 text-center">
          <a href="https://mobile.twitter.com/home" class="twitter"><i class="bx bxl-twitter"></i></a>
          <a href="https://m.facebook.com/" class="facebook"><i class="bx bxl-facebook"></i></a>
          <a href="https://instagram.com/ssenyongaemma5" class="instagram"><i class="bx bxl-instagram"></i></a>
          <a href="https://www.youtube.com/channel/UC2wIRf1U9xXwjRi5buatGJQ" class="google-plus"><i class="bx bxl-youtube"></i></a>
          <a href="https://github.com/SsenyongaEmma" class="linkedin"><i class="bx bxl-github"></i></a>
        </div>
      </div>

      <nav id="navbar" class="nav-menu navbar">
        <ul>
          <li><a href="#hero" class="nav-link scrollto active"><i class="bx bx-home"></i> <span>Home</span></a></li>
          <li><a href="#about" class="nav-link scrollto"><i class="bx bx-user"></i> <span>About</span></a></li>
          <li><a href="#resume" class="nav-link scrollto"><i class="bx bx-file-blank"></i> <span>Resume</span></a></li>
          <li><a href="#portfolio" class="nav-link scrollto"><i class="bx bx-book-content"></i> <span>Portfolio</span></a></li>
          <li><a href="#services" class="nav-link scrollto"><i class="bx bx-server"></i> <span>Services</span></a></li>
          <li><a href="#contact" class="nav-link scrollto"><i class="bx bx-envelope"></i> <span>Contact</span></a></li>
        </ul>
      </nav><!-- .nav-menu -->
    </div>
  </header><!-- End Header -->

  <!-- ======= Hero Section ======= -->
  <section id="hero"  class="d-flex flex-column justify-content-center align-items-center">
    <div class="hero-container"  data-aos="fade-in">
      <h1>Ssenyonga Emma</h1>
      <p>I'm a <span class="typed" data-typed-items="Programmer, Developer, Freelancer, Pentester"></span></p>
    </div>
  </section><!-- End Hero -->

  <main id="main">

    <!-- ======= About Section ======= -->
    <section id="about" class="about">
      <div class="container">

        <div class="section-title">
          <h2>About</h2>
          <p>I'm a self taught programmer, developer, freelancer and a pentester, I progressed in an online computer science course for the Harvard
             University's introduction to the intellectual enterprises of computer
             science and the art of programming (CS50) where I achieved Certificate on completion of CS50,
             including ten problem sets, eight labs and one final project.  which is instructed by: <br> <span> <strong>David J. Malan</strong> </span>, 
             <span> <strong>Doug Lloyd</strong> </span> and <span> <strong>Brian Yu</strong> </span> via edX.
             <br>
             I went on to learn more cyber-security skills from CISCO Networking Academy where I also achieved the 
             introduction to cyber-security badge

          </p>
        </div>

        <div class="row">
          <div class="col-lg-4" data-aos="fade-right">
            <img src="{% static 'assets/img/emma_dante.jpg' %}" class="img-fluid" alt="">
          </div>
          <div class="col-lg-8 pt-4 pt-lg-0 content" data-aos="fade-left">
            <h3>Programmer &amp; Web Developer.</h3>
            <p class="fst-italic">
              A full-stack developer of both android and web apps, willing to work with other developer teams
              in order to gain more experience in the tech-community.
            </p>
            <div class="row">
              <div class="col-lg-6">
                <ul>
                  <li><i class="bi bi-chevron-right"></i> <strong>Website:</strong> <span>www.example.com</span></li>
                  <li><i class="bi bi-chevron-right"></i> <strong>Phone:</strong> <span>+256-741-285-922</span></li>
                  <li><i class="bi bi-chevron-right"></i> <strong>City:</strong> <span>Kampala, Uganda</span></li>
                </ul>
              </div>
              <div class="col-lg-6">
                <ul>
                  <li><i class="bi bi-chevron-right"></i> <strong>Achievement:</strong> <span>Certificate</span></li>
                  <li><i class="bi bi-chevron-right"></i> <strong>Email:</strong> <span>mujjungajets@gmail.com</span></li>
                  <li><i class="bi bi-chevron-right"></i> <strong>Freelance:</strong> <span>Available</span></li>
                </ul>
              </div>
            </div>
            <p>
              It's a skill to master security in the technology industries, this is why I progressed in recieving 
              a verified introduction to cybersecurity badge from CISCO Networking Academy also to progress more to it's Professional level 

            </p>
          </div>
        </div>

      </div>
    </section><!-- End About Section -->

    <!-- ======= Facts Section ======= -->
    <section id="facts" class="facts">
      <div class="container">

        <div class="section-title">
          <h2>Facts</h2>
          <p> <span> <em>"</em> </span> There's no need even to have a College degree at all, even high school. I mean, if somebody graduated from agreet University that may be
            an indication that they wil be capable of great things, but it's not necessarily the case. <br> You Know, if you at, say people like Bill Gates
            or Larry Ellison , steve Jobs, these guys didn't graduated from College. But if you had a chance to hire them, of course, that would be a good idea.
            <br> So, you Know, looking just for evidence of exceptional ability and if there's a track record of exceptional achievement, then it's likely that will
            continue into the future. <br> When it comes to technology everything is for free to learn, it's just a skill to know how to use the internet and learn from 
            verious sites. 
            <br>
            <p>I think colleges are basically for fun and to prove you can do your chores, but they're not for learning so I don't
              consider going to College evidence of exceptional ability. In fact, ideally, you dropped out and did something
              <span><em>"</em></span> <em> <sub> Elon Mask</sub></em>
            </p>
            
          </p>
        </div>

        <div class="row no-gutters">

          <div class="col-lg-3 col-md-6 d-md-flex align-items-md-stretch" data-aos="fade-up">
            <div class="count-box">
              <i class="bi bi-emoji-smile"></i>
              <span data-purecounter-start="0" data-purecounter-end="232" data-purecounter-duration="1" class="purecounter"></span>
              <p><strong>Happy Clients</strong> Billbrain Technology </p>
            </div>
          </div>

          <div class="col-lg-3 col-md-6 d-md-flex align-items-md-stretch" data-aos="fade-up" data-aos-delay="100">
            <div class="count-box">
              <i class="bi bi-journal-richtext"></i>
              <span data-purecounter-start="0" data-purecounter-end="10" data-purecounter-duration="1" class="purecounter"></span>
              <p><strong>Projects</strong> <br> Billbrain Institute of technology android app <br>
              CS50 final project. etc</p>
            </div>
          </div>

          <div class="col-lg-3 col-md-6 d-md-flex align-items-md-stretch" data-aos="fade-up" data-aos-delay="200">
            <div class="count-box">
              <i class="bi bi-headset"></i>
              <span data-purecounter-start="0" data-purecounter-end="6" data-purecounter-duration="1" class="purecounter"></span>
              <p><strong>Hours Of Support</strong> <br> week (Monday - Friday)</p>
            </div>
          </div>

          <div class="col-lg-3 col-md-6 d-md-flex align-items-md-stretch" data-aos="fade-up" data-aos-delay="300">
            <div class="count-box">
              <i class="bi bi-people"></i>
              <span data-purecounter-start="0" data-purecounter-end="32" data-purecounter-duration="1" class="purecounter"></span>
              <p><strong>Hard Workers</strong><br> Comminted to change the world of technology to our customers</p>
            </div>
          </div>

        </div>

      </div>
    </section><!-- End Facts Section -->

    <!-- ======= Skills Section ======= -->
    <section id="skills" class="skills section-bg">
      <div class="container">

        <div class="section-title">
          <h2>Skills</h2>
          <p> Well, first of all, you don't need College and learn stuff. Okey. Everything is available for free. You can learn anything you want for free.
            it is not a question of learning </p>
        </div>

        <div class="row skills-content">

          <div class="col-lg-6" data-aos="fade-up">

            <div class="progress">
              <span class="skill">HTML <i class="val">100%</i></span>
              <div class="progress-bar-wrap">
                <div class="progress-bar" role="progressbar" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100"></div>
              </div>
            </div>

            <div class="progress">
              <span class="skill">CSS <i class="val">65%</i></span>
              <div class="progress-bar-wrap">
                <div class="progress-bar" role="progressbar" aria-valuenow="65" aria-valuemin="0" aria-valuemax="100"></div>
              </div>
            </div>

            <div class="progress">
              <span class="skill">JavaScript <i class="val">50%</i></span>
              <div class="progress-bar-wrap">
                <div class="progress-bar" role="progressbar" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100"></div>
              </div>
            </div>
            <div class="progress">
              <span class="skill">SQL <i class="val">75%</i></span>
              <div class="progress-bar-wrap">
                <div class="progress-bar" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100"></div>
              </div>
            </div>

          </div>

          <div class="col-lg-6" data-aos="fade-up" data-aos-delay="100">

            <div class="progress">
              <span class="skill">C <i class="val">80%</i></span>
              <div class="progress-bar-wrap">
                <div class="progress-bar" role="progressbar" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100"></div>
              </div>
            </div>

            <div class="progress">
              <span class="skill">Python <i class="val">90%</i></span>
              <div class="progress-bar-wrap">
                <div class="progress-bar" role="progressbar" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100"></div>
              </div>
            </div>

            <div class="progress">
              <span class="skill">Java <i class="val">55%</i></span>
              <div class="progress-bar-wrap">
                <div class="progress-bar" role="progressbar" aria-valuenow="55" aria-valuemin="0" aria-valuemax="100"></div>
              </div>
            </div>
           

          </div>

        </div>

      </div>
    </section><!-- End Skills Section -->

    <!-- ======= Resume Section ======= -->
    <section id="resume" class="resume">
      <div class="container">

        <div class="section-title">
          <h2>Resume</h2>
          <p>I'm seeking for employment as a developer, ready to work and learn  from Professional developers to gain Professional skill in developing, writing clean software,  implementing ideas and plans for software development cycle.
            <a href="{% static 'assets/Ssenyonga Emma Resume.pdf' %} " download="Emma Resume.pdf"><i>Download Resume</i></a>
          </p>
        </div>

        <div class="row">
          <div class="col-lg-6" data-aos="fade-up">
            <h3 class="resume-title">Sumary</h3>
            <div class="resume-item pb-0">
              <h4>Ssenyonga Emma</h4>
              <p><em>Innovative and deadline-driven programmer with 2+ years of experience designing and developing  android and web apps from the initial concept to final, polished project.</em></p>
              <ul>
                <li>Location: Kampala, Uganda</li>
                <li>(256) 741-285-922</li>
                <li>mujjungajets@gmail.com</li>
              </ul>
            </div>

            <h3 class="resume-title">Education</h3>
            <div class="resume-item">
              <h4>CS50's Web programming with Python &amp; JavaScript</h4>
              <h5>2022 - 2023</h5>
              <p><em>Harvard University</em></p>
              <p>Online via edX under harvard.edu</p>
            </div>
            <div class="resume-item">
              <h4>CS50x (Computer science 50x) &amp; The art of programming</h4>
              <h5>2022 - 2022</h5>
              <p><em>Harvard University</em></p>
              <p>Online via edX under harvard.edu </p>
            </div>
          </div>
          <div class="col-lg-6" data-aos="fade-up" data-aos-delay="100">
            <h3 class="resume-title">Education</h3>
            <div class="resume-item">
              <h4>Kitante Hill School </h4>
              <h5>2018 - 2020</h5>
              <p><em>Advanced Level</em></p>
              <ul>
                Achievement:
                <li>Uganda Advanced Certificate of Education</li>
                <li>Kitante at 60 years, Sports Certificate</li>
              </ul>
            </div>
            <div class="resume-item">
              <h4>Kitante Hill School</h4>
              <h5>2014 - 2018</h5>
              <p><em>Ordinary Level</em></p>
              <ul>
                Achievement:
                <li>Uganda Certificate of Education</li>
              </ul>
            </div>
            <div class="resume-item">
              <h4>Yudesi primary school</h4>
              <h5>2003 - 2014</h5>
              <p><em>Primary Level</em></p>
              <ul>
                Achievement:
                <li>Primary Leaving Education</li>
              </ul>
            </div>
          </div>
        </div>

      </div>
    </section><!-- End Resume Section -->

    <!-- ======= Portfolio Section ======= -->
    <section id="portfolio" class="portfolio section-bg">
      <div class="container">

        <div class="section-title">
          <h2>Portfolio</h2>
          <p>I'm simple, smart and ready to work with other IT tech developers to hit the limite of making the world of technology a better place</p>
        </div>

        <div class="row" data-aos="fade-up">
          <div class="col-lg-12 d-flex justify-content-center">
            <ul id="portfolio-flters">
              <li data-filter="*" class="filter-active">All</li>
              <li data-filter=".filter-app">App</li>
              
              <li data-filter=".filter-web">Website</li>
              <li data-filter=".filter-card">Achievement</li>
            </ul>
          </div>
        </div>

        <div class="row portfolio-container" data-aos="fade-up" data-aos-delay="100">

          <!-- <div class="col-lg-4 col-md-6 portfolio-item filter-app">
            <div class="portfolio-wrap">
              <img src="{% static 'assets/img/portfolio/portfolio-1.jpg' %}" class="img-fluid" alt="">
              <div class="portfolio-links">
                <a href="{% static 'assets/img/portfolio/portfolio-1.jpg' %}" data-gallery="portfolioGallery" class="portfolio-lightbox" title="App 1"><i class="bx bx-plus"></i></a>
                <a href="portfolio-details.html" title="More Details"><i class="bx bx-link"></i></a>
              </div>
            </div>
          </div> -->

          <!-- <div class="col-lg-4 col-md-6 portfolio-item filter-web">
            <div class="portfolio-wrap">
              <img src="{% static 'assets/img/portfolio/portfolio-2.jpg' %}" class="img-fluid" alt="">
              <div class="portfolio-links">
                <a href="{% static 'assets/img/portfolio/portfolio-2.jpg' %}" data-gallery="portfolioGallery" class="portfolio-lightbox" title="Web 3"><i class="bx bx-plus"></i></a>
                <a href="portfolio-details.html" title="More Details"><i class="bx bx-link"></i></a>
              </div>
            </div>
          </div> -->

          <!-- <div class="col-lg-4 col-md-6 portfolio-item filter-app">
            <div class="portfolio-wrap">
              <img src="{% static 'assets/img/portfolio/portfolio-3.jpg' %}" class="img-fluid" alt="">
              <div class="portfolio-links">
                <a href="{% static 'assets/img/portfolio/portfolio-3.jpg' %}" data-gallery="portfolioGallery" class="portfolio-lightbox" title="App 2"><i class="bx bx-plus"></i></a>
                <a href="portfolio-details.html" title="More Details"><i class="bx bx-link"></i></a>
              </div>
            </div>
          </div> -->

          <div class="col-lg-4 col-md-6 portfolio-item filter-card">
            <div class="portfolio-wrap">
              <img src="{% static 'assets/img/portfolio/introduction-to-cybersecurity.png' %}" class="img-fluid" alt="">
              <div class="portfolio-links">
                <a href="{% static 'assets/img/portfolio/introduction-to-cybersecurity.png' %}" data-gallery="portfolioGallery" class="portfolio-lightbox" title="CISCO Networking Academy badge"><i class="bx bx-plus"></i></a>
                <!-- <a href="portfolio-details.html" title="More Details"><i class="bx bx-link"></i></a> -->
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 portfolio-item filter-web">
            <div class="portfolio-wrap">
              <img src="{% static 'assets/img/portfolio/CS50 cert.png' %}" class="img-fluid" alt="">
              <div class="portfolio-links">
                <a href="{% static 'assets/img/portfolio/CS50 cert.png' %}" data-gallery="portfolioGallery" class="portfolio-lightbox" title="CS50 certificate "><i class="bx bx-plus"></i></a>
                <!-- <a href="portfolio-details.html" title="More Details"><i class="bx bx-link"></i></a> -->
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 portfolio-item filter-app">
            <div class="portfolio-wrap">
              <img src="{% static 'assets/img/portfolio/bit.jpg' %}" class="img-fluid" alt="">
              <div class="portfolio-links">
                <a href="{% static 'assets/img/portfolio/bit.jpg' %}" data-gallery="portfolioGallery" class="portfolio-lightbox" title="Billbrain Institute of technology App"><i class="bx bx-plus"></i></a>
                <p>Find it on the playstore</p>
                <!-- <a href="portfolio-details.html" title="More Details"><i class="bx bx-link"></i></a> -->
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 portfolio-item filter-card">
            <div class="portfolio-wrap">
              <img src="{% static 'assets/img/portfolio/CS50 cert.png' %}" class="img-fluid" alt="">
              <div class="portfolio-links">
                <a href="{% static 'assets/img/portfolio/CS50 cert.png' %}" data-gallery="portfolioGallery" class="portfolio-lightbox" title="CS50 certificate"><i class="bx bx-plus"></i></a>
                <!-- <a href="portfolio-details.html" title="More Details"><i class="bx bx-link"></i></a> -->
              </div>
            </div>
          </div>

          <!-- <div class="col-lg-4 col-md-6 portfolio-item filter-card">
            <div class="portfolio-wrap">
              <img src="{% static 'assets/img/portfolio/portfolio-8.jpg' %}" class="img-fluid" alt="">
              <div class="portfolio-links">
                <a href="{% static 'assets/img/portfolio/portfolio-8.jpg' %}" data-gallery="portfolioGallery" class="portfolio-lightbox" title="Card 3"><i class="bx bx-plus"></i></a>
                <a href="portfolio-details.html" title="More Details"><i class="bx bx-link"></i></a>
              </div>
            </div>
          </div> -->

          <!-- <div class="col-lg-4 col-md-6 portfolio-item filter-web">
            <div class="portfolio-wrap">
              <img src="{% static 'assets/img/portfolio/portfolio-9.jpg' %}" class="img-fluid" alt="">
              <div class="portfolio-links">
                <a href="{% static 'assets/img/portfolio/portfolio-9.jpg' %}" data-gallery="portfolioGallery" class="portfolio-lightbox" title="Web 3"><i class="bx bx-plus"></i></a>
                <a href="portfolio-details.html" title="More Details"><i class="bx bx-link"></i></a>
              </div>
            </div>
          </div> -->

        </div>

      </div>
    </section><!-- End Portfolio Section -->

    <!-- ======= Services Section ======= -->
    <section id="services" class="services">
      <div class="container">

        <div class="section-title">
          <h2>Services</h2>
          <p>I offer the following servers to my customers</p>
        </div>

        <div class="row">
          <div class="col-lg-4 col-md-6 icon-box" data-aos="fade-up">
            <div class="icon"><i class="bi bi-android"></i></div>
            <h4 class="title"><a href="">Android Development</a></h4>
            <p class="description">I develop both front-end and back-end development of android apps best on the customers designs</p>
          </div>
          <div class="col-lg-4 col-md-6 icon-box" data-aos="fade-up" data-aos-delay="100">
            <div class="icon"><i class="bi bi-code"></i></div>
            <h4 class="title"><a href="">Web Application Development</a></h4>
            <p class="description">I develop both dynamic and complex web-apps to customers</p>
          </div>
         
         
          <div class="col-lg-4 col-md-6 icon-box" data-aos="fade-up" data-aos-delay="500">
            <div class="icon"><i class="bi bi-calendar4-week"></i></div>
            <h4 class="title"><a href="">Communication</a></h4>
            <p class="description">Updating customers on their progressing development cycle  </p>
          </div>
        </div>

      </div>
    </section><!-- End Services Section -->

 

    <!-- ======= Contact Section ======= -->
    <section id="contact" class="contact">
      <div class="container">

        <div class="section-title">
          <h2>Contact</h2>
          <p> Let's make development more interesting and join me on your team of developers via.</p>
        </div>

        <div class="row" data-aos="fade-in">

          <div class="col-lg-5 d-flex align-items-stretch">
            <div class="info">
              <div class="address">
                <i class="bi bi-geo-alt"></i>
                <h4>Location:</h4>
                <p>Kampala, Uganda</p>
              </div>

              <div class="email">
                <i class="bi bi-envelope"></i>
                <h4>Email:</h4>
                <p>mujjungajets@gmail.com</p>
              </div>

              <div class="phone">
                <i class="bi bi-phone"></i>
                <h4>Call:</h4>
                <p>+256-741-285-922</p>
              </div>

              <!-- <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d12097.433213460943!2d-74.0062269!3d40.7101282!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xb89d1fe6bc499443!2sDowntown+Conference+Center!5e0!3m2!1smk!2sbg!4v1539943755621" frameborder="0" style="border:0; width: 100%; height: 290px;" allowfullscreen></iframe> -->
            </div>

          </div>

          <div class="col-lg-7 mt-5 mt-lg-0 d-flex align-items-stretch">
            <form action="client" method="post" role="form" class="php-email-form">
              {% csrf_token %}
              <div class="row">
                <div class="form-group col-md-6">
                  <label for="name">Your Name</label>
                  <input type="text" name="name" class="form-control" id="name" required>
                </div>
                <div class="form-group col-md-6">
                  <label for="name">Your Email</label>
                  <input type="email" class="form-control" name="email" id="email" required>
                </div>
              </div>
              <div class="form-group">
                <label for="name">Subject</label>
                <input type="text" class="form-control" name="subject" id="subject" required>
              </div>
              <div class="form-group">
                <label for="name">Message</label>
                <textarea class="form-control" name="message" rows="10" required></textarea>
              </div>
              <div class="my-3">
                <div class="loading">Loading</div>
                <div class="error-message">Your message has been sent. Thank you!</div>
                <div class="sent-message">Your message has been sent. Thank you!</div>
              </div>
              <div class="text-center"><button type="submit">Send Message</button></div>
            </form>
          </div>

        </div>

      </div>
    </section><!-- End Contact Section -->

  </main><!-- End #main -->

  <!-- ======= Footer ======= -->
  <footer id="footer">
    <div class="container">
      <div class="copyright">
        &copy; Copyright <strong><span>2022 Ssenyonga Emma</span></strong>
      </div>
      <div class="credits">
        <!-- All the links in the footer should remain intact. -->
        <!-- You can delete the links only if you purchased the pro version. -->
        <!-- Licensing information: https://bootstrapmade.com/license/ -->
        <!-- Purchase the pro version with working PHP/AJAX contact form: https://bootstrapmade.com/iportfolio-bootstrap-portfolio-websites-template/ -->
        <!-- Designed by <a href="https://bootstrapmade.com/">BootstrapMade</a> -->
      </div>
    </div>
  </footer><!-- End  Footer -->

  <a href="#" class="back-to-top d-flex align-items-center justify-content-center"><i class="bi bi-arrow-up-short"></i></a>

  <!-- Vendor JS Files -->
  <script src="{% static 'assets/vendor/purecounter/purecounter_vanilla.js' %}"></script>
  <script src="{% static 'assets/vendor/aos/aos.js' %}"></script>
  <script src="{% static 'assets/vendor/bootstrap/js/bootstrap.bundle.min.js' %}"></script>
  <script src="{% static 'assets/vendor/glightbox/js/glightbox.min.js' %}"></script>
  <script src="{% static 'assets/vendor/isotope-layout/isotope.pkgd.min.js' %}"></script>
  <script src="{% static 'assets/vendor/swiper/swiper-bundle.min.js' %}"></script>
  <script src="{% static 'assets/vendor/typed.js/typed.min.js' %}"></script>
  <script src="{% static 'assets/vendor/waypoints/noframework.waypoints.js' %}"></script>
  <script src="{% static 'assets/vendor/php-email-form/validate.js' %}"></script>

  <!-- Template Main JS File -->
  <script src="{% static 'assets/js/main.js' %}"></script>

</body>

</html>
