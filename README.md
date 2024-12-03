<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Oviya Portfolio</title>

  <!--
    - favicon
  -->
  <link rel="shortcut icon" href="./images/logo.ico" type="image/x-icon">

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

    <aside class="sidebar" data-sidebar="">

      <div class="sidebar-info">

        <figure class="avatar-box">
          <img src="./assets/images/my-avatar.png" alt="Om Kharche" width="80">
          <img src="./assets/images/waving-hand.gif" class="handwave zoom-effect" id="controlledGif">
        </figure>


        <div class="info-content">
          <h1 class="name" title="Om Kharche">Kasetty Nanda Kumar</h1>

          <p class="title">UI/UX Developer</p>
        </div>

        <button class="info_more-btn" data-sidebar-btn="">
          <span>Show Contacts</span>

          <ion-icon name="chevron-down" role="img" class="md hydrated" aria-label="chevron down"></ion-icon>
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

              <a href="mailto:omtestmail@gmail.com" class="contact-link">royalnandakumar@gmail.com</a>
            </div>

          </li>

          <li class="contact-item">

            <div class="icon-box">
              <img src="./assets/images/mob.gif" width="25px">
            </div>

            <div class="contact-info">
              <p class="contact-title">Phone</p>

              <a href="tel:+918919133190" class="contact-link">+91 8919133190</a>
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

              <address>Chennai, India</address>
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
            <a href="https://www.linkedin.com/in/kasetty-nanda-kumar/" class="social-link">
              <ion-icon name="logo-linkedin" role="img" class="md hydrated" aria-label="logo linkedin"></ion-icon>
            </a>
          </li>

          <li class="social-item">
            <a href="https://www.instagram.com/nanda_kumar_kasetty/" class="social-link">
              <ion-icon name="logo-instagram" role="img" class="md hydrated" aria-label="logo instagram"></ion-icon>
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
            <button class="navbar-link  active" data-nav-link="">About</button>
          </li>

          <li class="navbar-item">
            <button class="navbar-link" data-nav-link="">Background</button>
          </li>

          <li class="navbar-item">
            <button class="navbar-link" data-nav-link="">Projects</button>
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
            With over 2.5 years of comprehensive experience in UI/UX Development, I have played a dual role as both a UI
            and UX Developer, contributing to various web applications, websites, and portals. My focus has been on
            creating user-friendly, functional, and visually appealing interfaces that deliver optimal digital
            experiences. I am proficient in HTML, CSS, SCSS, Bootstrap, Material UI, JavaScript, and the React JS
            framework, ensuring the technical implementation aligns with the latest standards. Additionally, </p>

          <p>I have a strong background in the UX design process, including gathering and analyzing requirements,
            developing
            information architecture, crafting wireframes and prototypes, and executing visual design. My approach
            ensures that every product I work on is not only functional but also intuitive and aesthetically engaging.
          </p>

        </section>


        <!--
          - service
        -->

        <section class="service">

          <h3 class="h3 service-title">What i'm doing</h3>

          <ul class="service-list">

            <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/dev-gif.gif" alt="design icon" width="80">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">User experience Design</h4>

                <p class="service-item-text">
                  Information architectures, Wireframes, Prototypes and Visual Designs
                </p>
              </div>

            </li>

            <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/design-gif.gif" alt="Web development icon" width="80">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">Web development</h4>

                <p class="service-item-text">
                  High-quality development of web-sites and web-applications at the professional level.
                </p>
              </div>

            </li>

            <!-- <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/icon-app.svg" alt="mobile app icon" width="40">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">Mobile apps designs</h4>

                <p class="service-item-text">
                  Professional development of applications for iOS and Android.
                </p>
              </div>

            </li>

            <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/icon-photo.svg" alt="camera icon" width="40">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">Photography</h4>

                <p class="service-item-text">
                  I make high-quality photos of any category at a professional level.
                </p>
              </div>

            </li> -->

          </ul>

        </section>


        <!--
          - testimonials
        -->

        <section class="testimonials">

          <h3 class="h3 testimonials-title">Testimonials</h3>

          <ul class="testimonials-list has-scrollbar">

            <li class="testimonials-item">
              <div class="content-card" data-testimonials-item="">

                <figure class="testimonials-avatar-box">
                  <img src="./assets/images/thumb-up-dynamic-color.png" alt="thumb-up" width="40" data-testimonials-avatar="">
                </figure>

                <h4 class="h4 testimonials-item-title" data-testimonials-title=""></h4>

                <div class="testimonials-text" data-testimonials-text="">
                  <p>
                    I prioritize client collaboration by fostering open and transparent communication throughout the
                    project. By actively engaging in discussions and gathering feedback, I ensure the final product
                    aligns perfectly with the client’s vision. This approach builds trust and delivers results that meet
                    and exceed expectations
                  </p>
                </div>

              </div>
            </li>

            <li class="testimonials-item">
              <div class="content-card" data-testimonials-item="">

                <figure class="testimonials-avatar-box">
                  <img src="./assets/images/clock-dynamic-color.png" alt="Jessica miller" width="40" data-testimonials-avatar="">
                </figure>

                <h4 class="h4 testimonials-item-title" data-testimonials-title=""></h4>

                <div class="testimonials-text" data-testimonials-text="">
                  <p>
                    I’m very flexible with time zone communications, ensuring that I'm available to collaborate with
                    clients regardless of their location. This flexibility allows for seamless coordination and timely
                    responses, making the project process smooth and efficient.
                  </p>
                </div>

              </div>
            </li>

            <li class="testimonials-item">
              <div class="content-card" data-testimonials-item="">

                <figure class="testimonials-avatar-box">
                  <img src="./assets/images/computer-dynamic-color.png" alt="Emily evans" width="40" data-testimonials-avatar="">
                </figure>

                <h4 class="h4 testimonials-item-title" data-testimonials-title=""></h4>

                <div class="testimonials-text" data-testimonials-text="">
                  <p>
                    My tech stack includes HTML, CSS, SCSS, Bootstrap, Material UI, JavaScript, React JS, Figma, and Adobe XD.
                  </p>
                </div>

              </div>
            </li>



          </ul>

        </section>


        <!--
          - testimonials modal
        -->

        <div class="modal-container" data-modal-container="">

          <div class="overlay" data-overlay=""></div>

          <section class="testimonials-modal">

            <button class="modal-close-btn" data-modal-close-btn="">
              <ion-icon name="close-outline" role="img" class="md hydrated" aria-label="close outline"></ion-icon>
            </button>

            <div class="modal-img-wrapper">
              <figure class="modal-avatar-box">
                <img src="./assets/images/avatar-1.png" alt="Daniel lewis" width="80" data-modal-img="">
              </figure>

              <img src="./assets/images/icon-quote.svg" alt="quote icon">
            </div>

            <div class="modal-content">

              <h4 class="h3 modal-title" data-modal-title="">Daniel lewis</h4>

              <div data-modal-text="">
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

          <h3 class="h3 clients-title">My approach</h3>

          <ul class="clients-list has-scrollbar">

            <li class="clients-item">
              <a href="#">
                <img src="./assets/images/phase1.png" alt="phase1">
              </a>
            </li>

            <li class="clients-item">
              <a href="#">
                <img src="./assets/images/phase2.png" alt="phase2">
              </a>
            </li>

            <li class="clients-item">
              <a href="#">
                <img src="./assets/images/phase3.png" alt="phase3">
              </a>
            </li>

            <li class="clients-item">
              <a href="#">
                <img src="./assets/images/phase4.png" alt="phase4">
              </a>
            </li>

            <li class="clients-item">
              <a href="#">
                <img src="./assets/images/phase5.png" alt="phase5">
              </a>
            </li>

            

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
              <ion-icon name="book-outline" role="img" class="md hydrated" aria-label="book outline"></ion-icon>
            </div>

            <h3 class="h3">Education</h3>
          </div>

          <ol class="timeline-list">

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Saveetha School of Engineering </h4>

              <span>2017 — 2021</span>

              <p class="timeline-text">
                Completed BE Mechanical Engineering in SSE Chennai
              </p>

            </li>

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Class 12th</h4>

              <span>2015 — 2017</span>

              <p class="timeline-text">
                Completed 12th from Narayana Jr. Collage - Board of Intermediate Education Andhra Pradesh, Kadapa 
              </p>

            </li>

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Class 10th</h4>

              <span>2015</span>

              <p class="timeline-text">
                Completed 12th from D.A.V High School - Board of Secondary Education Andhra Pradesh, Kadapa 
              </p>

            </li>

          </ol>

        </section>

        <section class="timeline">

          <div class="title-wrapper">
            <div class="icon-box">
              <ion-icon name="book-outline" role="img" class="md hydrated" aria-label="book outline"></ion-icon>
            </div>

            <h3 class="h3">Experience</h3>
          </div>

          <ol class="timeline-list">

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">UI/UX Engineer</h4>

              <span>2021 — 2024</span>

              <p class="timeline-text">
                With over 2.5 years of comprehensive experience in UI/UX Development from Avasoft Chennai
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
          <h2 class="h2 article-title">Portfolio</h2>
        </header>

        <section class="projects">

          <ul class="filter-list">

            <li class="filter-item">
              <button class="active" data-filter-btn="">All</button>
            </li>

            <li class="filter-item">
              <button data-filter-btn="">Web design</button>
            </li>

            <li class="filter-item">
              <button data-filter-btn="">Applications</button>
            </li>

            <li class="filter-item">
              <button data-filter-btn="">Web development</button>
            </li>

          </ul>

          <div class="filter-select-box">

            <button class="filter-select" data-select="">

              <div class="select-value" data-selecct-value="">Select category</div>

              <div class="select-icon">
                <ion-icon name="chevron-down" role="img" class="md hydrated" aria-label="chevron down"></ion-icon>
              </div>

            </button>

            <ul class="select-list">

              <li class="select-item">
                <button data-select-item="">All</button>
              </li>

              <li class="select-item">
                <button data-select-item="">Web design</button>
              </li>

              <li class="select-item">
                <button data-select-item="">Applications</button>
              </li>

              <li class="select-item">
                <button data-select-item="">Web development</button>
              </li>

            </ul>

          </div>

          <ul class="project-list">

            <li class="project-item  active" data-filter-item="" data-category="web design">
              <a href="https://www.figma.com/proto/EcuHy1Ah5RUJima5xOn8ef/Real-Estate-Website-UI-Template?node-id=203-8&amp;t=qFdzZv5yNb1yntps-1&amp;scaling=min-zoom&amp;content-scaling=fixed&amp;page-id=45%3A2&amp;starting-point-node-id=203%3A8">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline" role="img" class="md hydrated" aria-label="eye outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-1.jpg" alt="realestate" loading="lazy">
                </figure>

                <h3 class="project-title">Real-Estate-Website-UI-Template</h3>

                <p class="project-category">Web design</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item="" data-category="web development">
              <a href="https://nandakumarroy.github.io/dash-board/">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline" role="img" class="md hydrated" aria-label="eye outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-2.png" alt="orizon" loading="lazy">
                </figure>

                <h3 class="project-title">React dash-board</h3>

                <p class="project-category">Web development</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item="" data-category="applications">
              <a href="https://www.figma.com/proto/vHVD6rAKPEwTgL9WTbbV6t/E-com-Mobile-Application-Design?node-id=1-2069&amp;t=BIgTja64cHYnh6BA-1&amp;scaling=min-zoom&amp;content-scaling=fixed&amp;page-id=1%3A1364&amp;starting-point-node-id=1%3A2263&amp;show-proto-sidebar=1">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline" role="img" class="md hydrated" aria-label="eye outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-3.jpg" alt="fundo" loading="lazy">
                </figure>

                <h3 class="project-title">E-Com Mobile App-UI-Template</h3>

                <p class="project-category">Applications</p>

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
  <script src="./assets/js/script.js"></script>

  <!--
    - ionicon link
  -->
  <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
  <script nomodule="" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>





</body>

</html>
