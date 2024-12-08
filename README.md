<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Oviya Mohan Portfolio</title>

  <!--
    - favicon
  -->
  <link rel="shortcut icon" href="./assets/images/logo.ico" type="image/x-icon">

  <!--
    - custom css link
  -->
  <link rel="stylesheet" href="./css/style.css">
  <!--
    - google font link
  -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">
</head>

<body>


  <!--
    - #MAIN
  -->

  <main>

    <!--
      - #SIDEBAR
    -->

    <aside class="sidebar" data-sidebar>

      <div class="sidebar-info">

        <figure class="avatar-box">
          <img src="./assets/images/my-avatar.jpg" alt="Om Kharche" width="80">
          <img src="./assets/images/waving-hand.gif" class="handwave" id="controlledGif">
        </figure>


        <div class="info-content">
          <h1 class="name" title="Om Kharche">Oviya Mohan</h1>

          <p class="title">UI/UX Designer</p>
        </div>

        <button class="info_more-btn" data-sidebar-btn>
          <span>Show Contacts</span>

          <ion-icon name="chevron-down"></ion-icon>
        </button>

      </div>

      <div class="sidebar-info_more">

        <div class="separator"></div>

        <ul class="contacts-list">

          <li class="contact-item">

            <div class="icon-box">
              <img src="./assets/images/mail.gif" width="30px">
            </div>

            <div class="contact-info">
              <p class="contact-title">Email</p>

              <a href="mailto:oviyacse2001@gmail.com" class="contact-link">oviyacse2001@gmail.com</a>
            </div>

          </li>

          <li class="contact-item">

            <div class="icon-box">
              <img src="./assets/images/mob.gif" width="25px">
            </div>

            <div class="contact-info">
              <p class="contact-title">Phone</p>

              <a href="tel:+916369035690" class="contact-link">+91 63669035690</a>
            </div>

          </li>

          <!-- <li class="contact-item">

            <div class="icon-box">
              <ion-icon name="calendar-outline"></ion-icon>
            </div>

            <div class="contact-info">
              <p class="contact-title">Birthday</p>

              <time datetime="1982-06-23">2 March, 2003</time>
            </div>

          </li> -->

          <li class="contact-item">

            <div class="icon-box">
              <img src="./assets/images/loc.gif" width="30px">
            </div>

            <div class="contact-info">
              <p class="contact-title">Location</p>

              <address>Namakkal, Tamilnadu.</address>
            </div>

          </li>

        </ul>

        <div class="separator"></div>

        <ul class="social-list">

          <!-- <li class="social-item">
            <a href="#" class="social-link">
              <ion-icon name="logo-facebook"></ion-icon>
            </a>
          </li> -->

          <li class="social-item">
            <a href="https://www.linkedin.com/in/oviya-m-a078a11a3/" class="social-link">
              <ion-icon name="logo-linkedin"></ion-icon>
            </a>
          </li>

          <li class="social-item">
            <a href="https://www.behance.net/oviya-uiux-designer" class="social-link">
              <ion-icon name="logo-behance"></ion-icon>
            </a>
          </li>

        </ul>

      </div>

    </aside>





    <!--
      - #main-content
    -->

    <div class="main-content">

      <!--
        - #NAVBAR
      -->

      <nav class="navbar">

        <ul class="navbar-list">

          <li class="navbar-item">
            <button class="navbar-link  active" data-nav-link>About</button>
          </li>

          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Background</button>
          </li>

          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Projects</button>
          </li>

          <!-- <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Blog</button>
          </li>

          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Contact</button>
          </li> -->

        </ul>

      </nav>





      <!--
        - #ABOUT
      -->

      <article class="about  active" data-page="about">

        <header>
          <h2 class="h2 article-title">About me</h2>
        </header>

        <section class="about-text">
          <p>
            I am a passionate and creative UI/UX Designer with 2.9 years of experience in designing intuitive, 
            user-centric interfaces for web and mobile applications. With a proven ability to combine user research 
            and design principles, I specialize in creating seamless experiences that enhance customer satisfaction 
            and drive business results. My mission is to turn complex problems into elegant, engaging solutions.
          </p>

          <p>
            I am proficient in Figma, Adobe XD, InVision, VS Code, HTML, CSS, SCSS, Bootstrap, and Sass, 
            ensuring that my designs are not only visually appealing but also technically sound and aligned with the
            latest industry standards.         
          </p>

        </section>


        <!--
          - service
        -->

        <section class="service">

          <h3 class="h3 service-title">What i'm doing</h3>

          <ul class="service-list">

            <!-- <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/dev-gif.gif" alt="design icon" width="80">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">Freelance Projects & Innovation</h4>

                <p class="service-item-text">
                  Designing and delivering user-friendly interfaces for various freelance projects, 
                  including a ride-booking app and a kids' routine management app, showcasing my ability to
                  translate complex ideas into engaging, functional designs.
                </p>
              </div>

            </li> -->

            <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/dev-gif.gif" alt="design icon" width="80">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">UI Design</h4>

                <p class="service-item-text">
                  Designing intuitive user interfaces through information architecture, user flows, wireframes, prototypes, and high-fidelity
                  mockups while aligning with brand identity and user needs.
                </p>
              </div>

            </li>

            <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/dev-gif.gif" alt="design icon" width="80">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">UI Development</h4>

                <p class="service-item-text">
                  Translating the designs into fully
                  functional, responsive interfaces using HTML, CSS, SCSS, Bootstrap, and Sass, ensuring clean, 
                  maintainable code that meets web standards for optimal performance and usability.
                </p>
              </div>

            </li>
            <!-- <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/design-gif.gif" alt="Web development icon" width="80">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">Skill Enhancement & Collaboration</h4>

                <p class="service-item-text">
                  Continuously improving my technical and creative skills in Figma, Adobe XD, HTML, CSS, 
                  and Bootstrap, while collaborating with clients and developers to align designs with business 
                  objectives and user needs.
                </p>
              </div>

            </li> -->
<!-- 
            <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/icon-app.svg" alt="mobile app icon" width="40">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">Client Collaboration</h4>

                <p class="service-item-text">
                 Collaborating with clients and stakeholders to translate business goals into design strategies while ensuring high-quality deliverables.
                </p>
              </div>

            </li>

            <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/icon-photo.svg" alt="camera icon" width="40">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">Client Collaboration</h4>

                <p class="service-item-text">
                  Collaborating with clients and stakeholders to translate business goals into design strategies while ensuring high-quality deliverables.
                </p>
              </div>

            </li>  -->

          </ul>

        </section>


        <!--
          - testimonials
        -->

        <section class="testimonials">

          <h3 class="h3 testimonials-title">Testimonials</h3>

          <ul class="testimonials-list has-scrollbar">

            <li class="testimonials-item">
              <div class="content-card" data-testimonials-item>

                <figure class="testimonials-avatar-box">
                  <img src="./assets/images/thumb-up-dynamic-color.png" alt="thumb-up" width="40"
                    data-testimonials-avatar>
                </figure>

                <h4 class="h4 testimonials-item-title" data-testimonials-title></h4>

                <div class="testimonials-text" data-testimonials-text>
                  <p>
                    "Thanks for all the help , you came at right time to help me with few Projects. Hope everything works better for you at your new job." — Freelance Client
                  </p>
                </div>

              </div>
            </li>

            <li class="testimonials-item">
              <div class="content-card" data-testimonials-item>

                <figure class="testimonials-avatar-box">
                  <img src="./assets/images/computer-dynamic-color.png" alt="Emily evans" width="40"
                  data-testimonials-avatar>
                </figure>

                <h4 class="h4 testimonials-item-title" data-testimonials-title></h4>

                <div class="testimonials-text" data-testimonials-text>
                  <p>
                    "Her attention to detail and dedication to understanding the end user resulted in a product that exceeded expectations."
                    — Freelance Client
                  </p>
                </div>

              </div>
            </li>

            <li class="testimonials-item">
              <div class="content-card" data-testimonials-item>

                <figure class="testimonials-avatar-box">
                
                    <img src="./assets/images/clock-dynamic-color.png" alt="Jessica miller" width="40"
                    data-testimonials-avatar>
                </figure>

                <h4 class="h4 testimonials-item-title" data-testimonials-title></h4>

                <div class="testimonials-text" data-testimonials-text>
                  <p>
                    "Oviya's ability to manage tight deadlines while maintaining high-quality work is unmatched. 
                    Thank you so much for Part of our project."
                    — Freelance Client
                  </p>
                </div>

              </div>
            </li>

          </ul>

        </section>


        <!--
          - testimonials modal
        -->

        <div class="modal-container" data-modal-container>

          <div class="overlay" data-overlay></div>

          <section class="testimonials-modal">

            <button class="modal-close-btn" data-modal-close-btn>
              <ion-icon name="close-outline"></ion-icon>
            </button>

            <div class="modal-img-wrapper">
              <figure class="modal-avatar-box">
                <img src="./assets/images/avatar-1.png" alt="Daniel lewis" width="80" data-modal-img>
              </figure>

              <img src="./assets/images/icon-quote.svg" alt="quote icon">
            </div>

            <div class="modal-content">

              <h4 class="h3 modal-title" data-modal-title>Daniel lewis</h4>

              <div data-modal-text>
                <p>
                  Richard was hired to create a corporate identity. We were very pleased with the work done. She has a
                  lot of experience
                  and is very concerned about the needs of client. Lorem ipsum dolor sit amet, ullamcous cididt
                  consectetur adipiscing
                  elit, seds do et eiusmod tempor incididunt ut laborels dolore magnarels alia.
                </p>
              </div>

            </div>

          </section>

        </div>


        <!--
          - My approach
        -->
        <section class="clients">

          <h3 class="h3">My approach</h3>

          <ul class="clients-list has-scrollbar">

            <li class="service-item clients-item">

              <div class="service-content-box">
                <span class="subheading">Phase 1</span>
                <h4 class="h4 service-item-title">Research & Discovery:</h4>
                <p class="service-item-text">
                  Conduct user interviews, competitor analysis, and market research to identify pain points and opportunities.
                </p>
              </div>

            </li>

            <li class="service-item clients-item">

              <div class="service-content-box">
                <span class="subheading">Phase 2</span>
                <h4 class="h4 service-item-title">Ideation & Strategy</h4>
                  <p class="service-item-text">
                    Create user personas, define workflows, and sketch wireframes to establish a clear design direction.
                  </p>
              </div>

            </li>

            <li class="service-item clients-item">

              <div class="service-content-box">
                <span class="subheading">Phase 3</span>
                <h4 class="h4 service-item-title">Design & Prototyping</h4>
                <p class="service-item-text">
                  Develop high-fidelity designs and interactive prototypes using tools like Figma, Sketch, and Adobe XD.
                </p>
              </div>

            </li>

            <li class="service-item clients-item">

              <div class="service-content-box">
                <span class="subheading">Phase 4</span>
                <h4 class="h4 service-item-title">Testing & Iteration</h4>
                <p class="service-item-text">
                  Conduct usability tests, gather feedback, and refine designs to ensure an optimal user experience.
                </p>
              </div>

            </li>

            <li class="service-item clients-item">

              <div class="service-content-box">
                <span class="subheading">Phase 5</span>
                <h4 class="h4 service-item-title">Delivery & Handoff</h4>
                  <p class="service-item-text">
                    Collaborate with developers for smooth implementation, providing assets and design specifications.
                  </p>
              </div>

            </li>
<!-- 
            <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/icon-app.svg" alt="mobile app icon" width="40">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">Client Collaboration</h4>

                <p class="service-item-text">
                 Collaborating with clients and stakeholders to translate business goals into design strategies while ensuring high-quality deliverables.
                </p>
              </div>

            </li>

            <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/icon-photo.svg" alt="camera icon" width="40">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">Client Collaboration</h4>

                <p class="service-item-text">
                  Collaborating with clients and stakeholders to translate business goals into design strategies while ensuring high-quality deliverables.
                </p>
              </div>

            </li>  -->

          </ul>

        </section>

      </article>





      <!--
        - #RESUME
      -->

      <article class="resume" data-page="background">

        <header>
          <h2 class="h2 article-title">Resume</h2>
        </header>
        
        <section class="timeline">

          <div class="title-wrapper">
            <div class="icon-box">
              <ion-icon name="book-outline"></ion-icon>
            </div>

            <h3 class="h3">Experience</h3>
          </div>

          <ol class="timeline-list">

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">UI/UX Engineer</h4>

              <span>2022 — 2024</span>

              <p class="timeline-text">
                Led the design and development of user interfaces for web and mobile applications, improving usability and user engagement.
                <br>
Delivered innovative solutions for complex design problems by conducting user research and usability testing.
<br>
Collaborated with cross-functional teams to ensure seamless implementation of designs, resulting in a 20% increase in task completion rates
              </p>

            </li>

           

          </ol>

        </section>

        <section class="timeline">

          <div class="title-wrapper">
            <div class="icon-box">
              <ion-icon name="book-outline"></ion-icon>
            </div>

            <h3 class="h3">Education</h3>
          </div>

          <ol class="timeline-list">

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Sri Lakshmi Ammal Engineering Collage - Chennai</h4>

              <span>2017 — 2021</span>

              <p class="timeline-text">
               BE - Computer Science & Engineering
              </p>

            </li>

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Govt Higher Secondary School - Namakkal</h4>

              <span>2016 — 2017</span>

              <p class="timeline-text">
               12th Standard
              </p>

            </li>

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Govt Higher Secondary School - Namakkal</h4>

              <span>2014 - 2015</span>

              <p class="timeline-text">
                10th Standard
              </p>

            </li>

          </ol>

        </section>


        <!-- <section class="skill">

          <h3 class="h3 skills-title">My skills</h3>

          <ul class="skills-list content-card">

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Web design</h5>
                <data value="80">80%</data>
              </div>

              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 80%;"></div>
              </div>

            </li>

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Graphic design</h5>
                <data value="70">70%</data>
              </div>

              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 70%;"></div>
              </div>

            </li>

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Branding</h5>
                <data value="90">90%</data>
              </div>

              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 90%;"></div>
              </div>

            </li>

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">WordPress</h5>
                <data value="50">50%</data>
              </div>

              <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 50%;"></div>
              </div>

            </li>

          </ul>

        </section> -->

      </article>





      <!--
        - #PORTFOLIO
      -->

      <article class="portfolio" data-page="projects">

        <header>
          <h2 class="h2 article-title" id="travelease">Portfolio</h2>
        </header>

        <section class="projects">

          <ul class="filter-list">

            <li class="filter-item">
              <button class="active" data-filter-btn>All</button>
            </li>

            <li class="filter-item">
              <button data-filter-btn>Website design</button>
            </li>

            <li class="filter-item">
              <button data-filter-btn>Mobile Applications</button>
            </li>

            <!-- <li class="filter-item">
              <button data-filter-btn></button>
            </li> -->

          </ul>

          <div class="filter-select-box">

            <button class="filter-select" data-select>

              <div class="select-value" data-selecct-value>Select category</div>

              <div class="select-icon">
                <ion-icon name="chevron-down"></ion-icon>
              </div>

            </button>

            <ul class="select-list">

              <li class="select-item">
                <button data-select-item>All</button>
              </li>

              <li class="select-item">
                <button data-select-item>Web design</button>
              </li>

              <li class="select-item">
                <button data-select-item>Applications</button>
              </li>

              <li class="select-item">
                <button data-select-item>Web development</button>
              </li>

            </ul>

          </div>

          <ul class="project-list">

            <li class="project-item  active" data-filter-item data-category="web design">
              <a href="Travelease.html">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/travelease-thumbnail.png" alt="realestate" loading="lazy">
                </figure>

                <h3 class="project-title">Travel Ease</h3>

                <p class="project-category">Website design(2024)</p>

              </a>
            </li>
            
            <li class="project-item  active" data-filter-item data-category="web design">
              <a href="Musicbeats.html">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/Musicbeats-thumbnail.png" alt="Music Intruments" loading="lazy">
                </figure>

                <h3 class="project-title">Music Beats</h3>

                <p class="project-category">Website design(2021)</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="web design">
              <a href="Jaguar.html">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/Jaguar-thumbnail.png" alt="Music Intruments" loading="lazy">
                </figure>

                <h3 class="project-title">Jaguar Page Redesign</h3>

                <p class="project-category">Website(2021)</p>

              </a>
            </li>
            
            <li class="project-item  active" data-filter-item data-category="web design">
              <a href="Fittrack.html">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/Musicbeats-thumbnail.png" alt="Music Intruments" loading="lazy">
                </figure>

                <h3 class="project-title">Fittrack</h3>

                <p class="project-category">Mobile Application(2024) - Case Study</p>

              </a>
            </li>
           
           

          </ul>

        </section>

      </article>





      <!--
        - #BLOG
      -->

      <!-- <article class="blog" data-page="blog">

        <header>
          <h2 class="h2 article-title">Blog</h2>
        </header>

        <section class="blog-posts">

          <ul class="blog-posts-list">

            <li class="blog-post-item">
              <a href="#">

                <figure class="blog-banner-box">
                  <img src="./assets/images/blog-1.jpg" alt="Design conferences in 2022" loading="lazy">
                </figure>

                <div class="blog-content">

                  <div class="blog-meta">
                    <p class="blog-category">Design</p>

                    <span class="dot"></span>

                    <time datetime="2022-02-23">Fab 23, 2022</time>
                  </div>

                  <h3 class="h3 blog-item-title">Design conferences in 2022</h3>

                  <p class="blog-text">
                    Veritatis et quasi architecto beatae vitae dicta sunt, explicabo.
                  </p>

                </div>

              </a>
            </li>

            <li class="blog-post-item">
              <a href="#">

                <figure class="blog-banner-box">
                  <img src="./assets/images/blog-2.jpg" alt="Best fonts every designer" loading="lazy">
                </figure>

                <div class="blog-content">

                  <div class="blog-meta">
                    <p class="blog-category">Design</p>

                    <span class="dot"></span>

                    <time datetime="2022-02-23">Fab 23, 2022</time>
                  </div>

                  <h3 class="h3 blog-item-title">Best fonts every designer</h3>

                  <p class="blog-text">
                    Sed ut perspiciatis, nam libero tempore, cum soluta nobis est eligendi.
                  </p>

                </div>

              </a>
            </li>

            <li class="blog-post-item">
              <a href="#">

                <figure class="blog-banner-box">
                  <img src="./assets/images/blog-3.jpg" alt="Design digest #80" loading="lazy">
                </figure>

                <div class="blog-content">

                  <div class="blog-meta">
                    <p class="blog-category">Design</p>

                    <span class="dot"></span>

                    <time datetime="2022-02-23">Fab 23, 2022</time>
                  </div>

                  <h3 class="h3 blog-item-title">Design digest #80</h3>

                  <p class="blog-text">
                    Excepteur sint occaecat cupidatat no proident, quis nostrum exercitationem ullam corporis suscipit.
                  </p>

                </div>

              </a>
            </li>

            <li class="blog-post-item">
              <a href="#">

                <figure class="blog-banner-box">
                  <img src="./assets/images/blog-4.jpg" alt="UI interactions of the week" loading="lazy">
                </figure>

                <div class="blog-content">

                  <div class="blog-meta">
                    <p class="blog-category">Design</p>

                    <span class="dot"></span>

                    <time datetime="2022-02-23">Fab 23, 2022</time>
                  </div>

                  <h3 class="h3 blog-item-title">UI interactions of the week</h3>

                  <p class="blog-text">
                    Enim ad minim veniam, consectetur adipiscing elit, quis nostrud exercitation ullamco laboris nisi.
                  </p>

                </div>

              </a>
            </li>

            <li class="blog-post-item">
              <a href="#">

                <figure class="blog-banner-box">
                  <img src="./assets/images/blog-5.jpg" alt="The forgotten art of spacing" loading="lazy">
                </figure>

                <div class="blog-content">

                  <div class="blog-meta">
                    <p class="blog-category">Design</p>

                    <span class="dot"></span>

                    <time datetime="2022-02-23">Fab 23, 2022</time>
                  </div>

                  <h3 class="h3 blog-item-title">The forgotten art of spacing</h3>

                  <p class="blog-text">
                    Maxime placeat, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                  </p>

                </div>

              </a>
            </li>

            <li class="blog-post-item">
              <a href="#">

                <figure class="blog-banner-box">
                  <img src="./assets/images/blog-6.jpg" alt="Design digest #79" loading="lazy">
                </figure>

                <div class="blog-content">

                  <div class="blog-meta">
                    <p class="blog-category">Design</p>

                    <span class="dot"></span>

                    <time datetime="2022-02-23">Fab 23, 2022</time>
                  </div>

                  <h3 class="h3 blog-item-title">Design digest #79</h3>

                  <p class="blog-text">
                    Optio cumque nihil impedit uo minus quod maxime placeat, velit esse cillum.
                  </p>

                </div>

              </a>
            </li>

          </ul>

        </section>

      </article> -->





      <!--
        - #CONTACT
      -->

      <!-- <article class="contact" data-page="contact">

        <header>
          <h2 class="h2 article-title">Contact</h2>
        </header>

        <section class="mapbox" data-mapbox>
          <figure>
            <iframe
              src="https://maps.google.com/maps?width=100%25&amp;height=600&amp;hl=en&amp;q=chennai+(My%20Business%20Name)&amp;t=&amp;z=14&amp;ie=UTF8&amp;iwloc=B&amp;output=embed"
              width="400" height="300" loading="lazy"></iframe>
          </figure>
        </section>



        <section class="contact-form">

          <h3 class="h3 form-title">Contact Form</h3>

          <form action="#" class="form" data-form>

            <div class="input-wrapper">
              <input type="text" name="fullname" class="form-input" placeholder="Full name" required data-form-input>

              <input type="email" name="email" class="form-input" placeholder="Email address" required data-form-input>
            </div>

            <textarea name="message" class="form-input" placeholder="Your Message" required data-form-input></textarea>

            <button class="form-btn" type="submit" disabled data-form-btn>
              <ion-icon name="paper-plane"></ion-icon>
              <span>Send Message</span>
            </button>

          </form>

        </section>

      </article> -->

    </div>

  </main>






  <!--
    - custom js link
  -->
  <script src="./js/script.js"></script>

  <!--
    - ionicon link
  -->
  <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
  <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>



</body>

</html>
