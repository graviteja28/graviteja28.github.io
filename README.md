<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vinay - Personal Portfolio</title>

  <!--
    - favicon
  -->
  <link rel="shortcut icon" href="./assets/images/logo.ico" type="image/x-icon">

  <!--
    - custom css link
  -->
  <link rel="stylesheet" href="./assets/css/style.css">

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
          <img src="./assets/images/myavatar.jpg" alt="Richard hanrick" width="80">
        </figure>

        <div class="info-content">
          <h1 class="name" title="Vinay Meesaraganda">Vinay Meesaraganda</h1>

          <p class="title">Data Analyst/Engineer</p>
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
              <ion-icon name="mail-outline"></ion-icon>
            </div>

            <div class="contact-info">
              <p class="contact-title">Email</p>

              <a href="mailto:raj.vinay2408@gmail.com" class="contact-link">raj.vinay2408@gmail.com</a>
            </div>

          </li>

          <li class="contact-item">

            <div class="icon-box">
              <ion-icon name="phone-portrait-outline"></ion-icon>
            </div>

            <div class="contact-info">
              <p class="contact-title">Phone</p>

              <a href="tel:+12014928306" class="contact-link">+1 (201) 492-8306</a>
            </div>

          </li>

          <!-- <li class="contact-item">

            <div class="icon-box">
              <ion-icon name="calendar-outline"></ion-icon>
            </div>

            <div class="contact-info">
              <p class="contact-title">Birthday</p>

              <time datetime="1982-06-23">March 11, 2000</time>
            </div>

          </li> -->

          <li class="contact-item">

            <div class="icon-box">
              <ion-icon name="location-outline"></ion-icon>
            </div>

            <div class="contact-info">
              <p class="contact-title">Location</p>

              <address>Jersey City, NJ, USA</address>
            </div>

          </li>

        </ul>

        <div class="separator"></div>

        <ul class="social-list">

          <li class="social-item">
            <a href="https://www.linkedin.com/in/vinaykiranraju/" class="social-link">
              <ion-icon name="logo-linkedin"></ion-icon>
            </a>
          </li>

          <li class="social-item">
            <a href="https://github.com/VinayMeesaraganda" class="social-link">
              <ion-icon name="logo-github"></ion-icon>
            </a>
          </li>

          <li class="social-item">
            <a href="https://www.instagram.com/vinay.__.24/" class="social-link">
              <ion-icon name="logo-instagram"></ion-icon>
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
            <button class="navbar-link" data-nav-link>Resume</button>
          </li>

          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Portfolio</button>
          </li>

          <!-- <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Blog</button>
          </li> -->

          <li class="navbar-item">
            <button class="navbar-link" data-nav-link>Contact</button>
          </li>

        </ul>

      </nav>





      <!--
        - #ABOUT
      -->

      <article class="about  active" data-page="about">

        <header>
          <h2 class="h2 article-title">Hi, I'm Vinay</h2>
        </header>

        <section class="about-text">

          <p>
            I'm a Master's student in Data Science with experience as a data engineer and a passion for data analytics. 
            I've obtained certifications from top companies in the industry, and this portfolio showcases some of my best work in 
            data cleaning, predictive modeling, and interactive visualization

          </p>
        </section>


        <!--
          - service
        -->

        <section class="service">

          <h3 class="h3 service-title">Certifications</h3>

          <ul class="service-list">

            <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/Google.png"
                 alt="Google Data Analyst" width="75",height="75">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">
                  <a href="https://coursera.org/share/c14762de661df356c7bca80093092c71" style="color:white;" style="text-align:left" >Coursera-Google Data Analyst</a>
                </h4>
                <p class="service-item-text">
                  <!-- The most modern and high-quality design made at a professional level. -->
                </p>
              </div>

            </li>

            <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/Tableau.png" 
                alt="Tableau Desktop Specialist" width="75",height="75">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">
                  <a href="https://www.credly.com/badges/23abb4fa-922c-419e-adff-eacdf98b3242/public_url" style="color:white;" >Tableau-Tableau Desktop Specialist</a>
                </h4>

                <p class="service-item-text">
                  <!-- High-quality development of sites at the professional level. -->
                </p>
              </div>

            </li>

            <!-- <li class="service-item">

              <div class="service-icon-box">
                <img src="./assets/images/icon-app.svg" alt="mobile app icon" width="40">
              </div>

              <div class="service-content-box">
                <h4 class="h4 service-item-title">Mobile apps</h4>

                <p class="service-item-text">
                  Professional development of applications for iOS and Android.
                </p>
              </div>

            </li> -->

            <!-- <li class="service-item">

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

        <!-- <section class="testimonials">

          <h3 class="h3 testimonials-title">Testimonials</h3>

          <ul class="testimonials-list has-scrollbar">

            <li class="testimonials-item">
              <div class="content-card" data-testimonials-item>

                <figure class="testimonials-avatar-box">
                  <img src="./assets/images/avatar-1.png" alt="Daniel lewis" width="60" data-testimonials-avatar>
                </figure>

                <h4 class="h4 testimonials-item-title" data-testimonials-title>Daniel lewis</h4>

                <div class="testimonials-text" data-testimonials-text>
                  <p>
                    Richard was hired to create a corporate identity. We were very pleased with the work done. She has a
                    lot of experience
                    and is very concerned about the needs of client. Lorem ipsum dolor sit amet, ullamcous cididt
                    consectetur adipiscing
                    elit, seds do et eiusmod tempor incididunt ut laborels dolore magnarels alia.
                  </p>
                </div>

              </div>
            </li>

            <li class="testimonials-item">
              <div class="content-card" data-testimonials-item>

                <figure class="testimonials-avatar-box">
                  <img src="./assets/images/avatar-2.png" alt="Jessica miller" width="60" data-testimonials-avatar>
                </figure>

                <h4 class="h4 testimonials-item-title" data-testimonials-title>Jessica miller</h4>

                <div class="testimonials-text" data-testimonials-text>
                  <p>
                    Richard was hired to create a corporate identity. We were very pleased with the work done. She has a
                    lot of experience
                    and is very concerned about the needs of client. Lorem ipsum dolor sit amet, ullamcous cididt
                    consectetur adipiscing
                    elit, seds do et eiusmod tempor incididunt ut laborels dolore magnarels alia.
                  </p>
                </div>

              </div>
            </li>

            <li class="testimonials-item">
              <div class="content-card" data-testimonials-item>

                <figure class="testimonials-avatar-box">
                  <img src="./assets/images/avatar-3.png" alt="Emily evans" width="60" data-testimonials-avatar>
                </figure>

                <h4 class="h4 testimonials-item-title" data-testimonials-title>Emily evans</h4>

                <div class="testimonials-text" data-testimonials-text>
                  <p>
                    Richard was hired to create a corporate identity. We were very pleased with the work done. She has a
                    lot of experience
                    and is very concerned about the needs of client. Lorem ipsum dolor sit amet, ullamcous cididt
                    consectetur adipiscing
                    elit, seds do et eiusmod tempor incididunt ut laborels dolore magnarels alia.
                  </p>
                </div>

              </div>
            </li>

            <li class="testimonials-item">
              <div class="content-card" data-testimonials-item>

                <figure class="testimonials-avatar-box">
                  <img src="./assets/images/avatar-4.png" alt="Henry william" width="60" data-testimonials-avatar>
                </figure>

                <h4 class="h4 testimonials-item-title" data-testimonials-title>Henry william</h4>

                <div class="testimonials-text" data-testimonials-text>
                  <p>
                    Richard was hired to create a corporate identity. We were very pleased with the work done. She has a
                    lot of experience
                    and is very concerned about the needs of client. Lorem ipsum dolor sit amet, ullamcous cididt
                    consectetur adipiscing
                    elit, seds do et eiusmod tempor incididunt ut laborels dolore magnarels alia.
                  </p>
                </div>

              </div>
            </li>

          </ul>

        </section> -->


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

              <time datetime="2021-06-14">14 June, 2021</time>

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
          - clients
        -->

        <section class="Featured">

          <h3 class="h3 clients-title">Featured</h3>

          <ul class="clients-list has-scrollbar">

            <li class="clients-item" data-filter-item data-category="tableau">
              <a href="https://github.com/VinayMeesaraganda/Tableau_Projects/blob/8f54ae0f8999d586b38ee55ff5f2c6bb70d3c3fc/NCAA%20Women%20Statistics.md">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/NCAA Women Statistics.png" alt="NCAA Women Statistics" loading="lazy">
                </figure>

                <h3 class="project-title">NCAA Women Statistics</h3>

                <p class="project-category">Tableau</p>

              </a>
            </li>

            <li class="clients-item" data-filter-item data-category="python">
              <a href="https://github.com/VinayMeesaraganda/CS668_Capstone_Project.git">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/Loan Prediction Python.jpg" alt="Loan Prediction using Python" loading="lazy">
                </figure>

                <h3 class="project-title">Loan Default Prediction</h3>

                <p class="project-category">Python</p>

              </a>
            </li>

            <li class="clients-item" data-filter-item data-category="tableau">
              <a href="https://github.com/VinayMeesaraganda/Tableau_Projects/blob/main/HR%20Analytics%20Dashboard.md">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/HR Analytics Dashboard.png" alt="HR Analytics Dashboard" loading="lazy">
                </figure>

                <h3 class="project-title">HR Analytics Dashboard</h3>

                <p class="project-category">Tableau</p>

              </a>
            </li>

            <li class="clients-item" data-filter-item data-category="python">
              <a href="https://github.com/VinayMeesaraganda/Python-Projects/tree/main/Patients%20Heart%20Failure%20Analysis">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/Heart failure.jpg" alt="Heart Failure Analysis" loading="lazy">
                </figure>

                <h3 class="project-title">Heart Failure Analysis</h3>

                <p class="project-category">Python</p>

              </a>
            </li>

            <!-- <li class="clients-item">
              <a href="#">
                <img src="./assets/images/logo-5-color.png" alt="client logo">
              </a>
            </li>

            <li class="clients-item">
              <a href="#">
                <img src="./assets/images/logo-6-color.png" alt="client logo">
              </a>
            </li> -->

          </ul>

        </section>

      </article>





      <!--
        - #RESUME
      -->

      <article class="resume" data-page="resume">

        <header>
          <h2 class="h2 article-title">Resume</h2>
        </header>

        <section class="timeline">

          <div class="title-wrapper">
            <div class="icon-box">
              <ion-icon name="book-outline"></ion-icon>
            </div>

            <h3 class="h3">Education</h3>
          </div>

          <ol class="timeline-list">

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Pace University - New York, NY</h4>

              <span>2022 — 2023</span>

              <p class="timeline-text">
                Master of Science (MS) in Data Science | Concentration : Data analytics & Machine Learning | GPA : 3.14/4
              </p>

            </li>

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Gitam University - Visakhapatnam, India</h4>

              <span>2017-2021</span>

              <p class="timeline-text">
                Bachelor of Technology in Electronics and Communication Engineering | GPA : 8.38/10 
              </p>

            </li>

            <!-- <li class="timeline-item">

              <h4 class="h4 timeline-item-title">High school of art and design</h4>

              <span>2002 — 2004</span>

              <p class="timeline-text">
                Duis aute irure dolor in reprehenderit in voluptate, quila voluptas mag odit aut fugit, sed consequuntur
                magni dolores
                eos.
              </p>

            </li> -->

          </ol>

        </section>

        <section class="timeline">

          <div class="title-wrapper">
            <div class="icon-box">
              <ion-icon name="book-outline"></ion-icon>
            </div>

            <h3 class="h3">Experience</h3>
          </div>

          <ol class="timeline-list">

            <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Data Engineer - Natsoft Corporation</h4>

              <span>2021 —2022</span>

              <p class="timeline-text">
                <h4 class="timeline-text">&#x2022; Design, develop and optimize data processing systems using Apache Spark, EMR, and Hive.</h4>
                <h4 class="timeline-text">&#x2022; Develop and maintain ETL pipelines using tools like Sqoop, Spark RDDs and data frames.</h4>
                <h4 class="timeline-text">&#x2022; Perform data quality analysis and profiling to ensure accuracy and completeness of data.</h4>
                <h4 class="timeline-text">&#x2022; Collaborate with cross-functional teams to understand business requirements and provide insights through data analysis.</h4>
              </p>

            </li>

            <!-- <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Art director</h4>

              <span>2013 — 2015</span>

              <p class="timeline-text">
                Nemo enims ipsam voluptatem, blanditiis praesentium voluptum delenit atque corrupti, quos dolores et
                quas molestias
                exceptur.
              </p>

            </li> -->

            <!-- <li class="timeline-item">

              <h4 class="h4 timeline-item-title">Web designer</h4>

              <span>2010 — 2013</span>

              <p class="timeline-text">
                Nemo enims ipsam voluptatem, blanditiis praesentium voluptum delenit atque corrupti, quos dolores et
                quas molestias
                exceptur.
              </p>

            </li> -->

          </ol>

        </section>

        <section class="skill">

          <h3 class="h3 skills-title">My skills</h3>

          <ul class="skills-list content-card">

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Big Data Technologies :</h5>
                <data value="80">Hadoop, MapReduce, Spark, HDFS, Sqoop,Nifi,Hive, Cloudera, HBase</data>
              </div>

              <!-- <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 80%;"></div>
              </div> -->

            </li>

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Programming Skills :</h5>
                <data value="70">Python, Scala, SQL</data>
              </div>

              <!-- <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 70%;"></div>
              </div> -->

            </li>

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Libraries :</h5>
                <data value="50">Python (Pandas, NumPy, Matplotlib, Seaborn scikit-learn, SciPy, TensorFlow)</data>
              </div>

              <!-- <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 50%;"></div>
              </div> -->

            </li>

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Cloud Services :</h5>
                <data value="90">Amazon Web Services, Microsoft Azure</data>
              </div>

              <!-- <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 90%;"></div>
              </div> -->

            </li>

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">Databases :</h5>
                <data value="50">MySQL, SQL Server, Oracle, HBase</data>
              </div>

              <!-- <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 50%;"></div>
              </div> -->

            </li>

            <li class="skills-item">

              <div class="title-wrapper">
                <h5 class="h5">visualization Tools :</h5>
                <data value="50">Tableau, MS EXCEL, Google Sheets</data>
              </div>

              <!-- <div class="skill-progress-bg">
                <div class="skill-progress-fill" style="width: 50%;"></div>
              </div> -->

            </li>

          </ul>

        </section>

      </article>





      <!--
        - #PORTFOLIO
      -->

      <!-- <article class="portfolio" data-page="portfolio">

        <header>
          <h2 class="h2 article-title">Portfolio</h2>
        </header>

        <section class="projects">

          <ul class="filter-list">

            <li class="filter-item">
              <button class="active" data-filter-btn>All</button>
            </li>

            <li class="filter-item">
              <button data-filter-btn>Tableau</button>
            </li>

            <li class="filter-item">
              <button data-filter-btn>Web development</button>
            </li>

            <li class="filter-item">
              <button data-filter-btn>Data Engineering</button>
            </li>

          </ul>

          <div class="filter-select-box">

            <button class="filter-select" data-select>

              <div class="select-value" data-select-value>Select category</div>

              <div class="select-icon">
                <ion-icon name="chevron-down"></ion-icon>
              </div>

            </button>

            <ul class="select-list">

              <li class="select-item">
                <button data-select-item>All</button>
              </li>

              <li class="select-item">
                <button data-select-item>Tableau</button>
              </li>

              <li class="select-item">
                <button data-select-item>Web development</button>
              </li>

              <li class="select-item">
                <button data-select-item>Data Engineering</button>
              </li>

            </ul>

          </div>

          <ul class="project-list">

            <li class="project-item  active" data-filter-item data-category="Tableau">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/NCAA Women Statistics.png" alt="NCAA Women Statistics" loading="lazy">
                </figure>

                <h3 class="project-title">NCAA Women Statistics</h3>

                <p class="project-category">Tableau</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="web development">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-2.png" alt="orizon" loading="lazy">
                </figure>

                <h3 class="project-title">Orizon</h3>

                <p class="project-category">Web development</p>

              </a>
            </li> -->

            <!-- <li class="project-item  active" data-filter-item data-category="web design">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-3.jpg" alt="fundo" loading="lazy">
                </figure>

                <h3 class="project-title">Fundo</h3>

                <p class="project-category">Web design</p>

              </a>
            </li> -->

            <!-- <li class="project-item  active" data-filter-item data-category="applications">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-4.png" alt="brawlhalla" loading="lazy">
                </figure>

                <h3 class="project-title">Brawlhalla</h3>

                <p class="project-category">Applications</p>

              </a>
            </li> -->

            <!-- <li class="project-item  active" data-filter-item data-category="web design">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-5.png" alt="dsm." loading="lazy">
                </figure>

                <h3 class="project-title">DSM.</h3>

                <p class="project-category">Web design</p>

              </a>
            </li> -->

            <!-- <li class="project-item  active" data-filter-item data-category="web design">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-6.png" alt="metaspark" loading="lazy">
                </figure>

                <h3 class="project-title">MetaSpark</h3>

                <p class="project-category">Web design</p>

              </a>
            </li> -->

            <!-- <li class="project-item  active" data-filter-item data-category="web development">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-7.png" alt="summary" loading="lazy">
                </figure>

                <h3 class="project-title">Summary</h3>

                <p class="project-category">Web development</p>

              </a>
            </li> -->

            <!-- <li class="project-item  active" data-filter-item data-category="applications">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-8.jpg" alt="task manager" loading="lazy">
                </figure>

                <h3 class="project-title">Task Manager</h3>

                <p class="project-category">Applications</p>

              </a>
            </li> -->

            <!-- <li class="project-item  active" data-filter-item data-category="web development">
              <a href="#">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/project-9.png" alt="arrival" loading="lazy">
                </figure>

                <h3 class="project-title">Arrival</h3>

                <p class="project-category">Web development</p>

              </a>
            </li> -->

          <!-- </ul>

        </section>

      </article> -->
<!--
        - #PORTFOLIO
      -->
      
      <article class="portfolio" data-page="portfolio">

        <header>
          <h2 class="h2 article-title">Portfolio</h2>
        </header>

        <section class="projects">

          <ul class="filter-list">

            <li class="filter-item">
              <button class="active" data-filter-btn>All</button>
            </li>

            <li class="filter-item">
              <button data-filter-btn>Tableau</button>
            </li>

            <li class="filter-item">
              <button data-filter-btn>Python</button>
            </li>

            <!-- <li class="filter-item">
              <button data-filter-btn>SQL</button>
            </li>

            <li class="filter-item">
              <button data-filter-btn>Excel</button>
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
                <button data-select-item>Tableau</button>
              </li>

              <li class="select-item">
                <button data-select-item>Python</button>
              </li>

              <!-- <li class="select-item">
                <button data-select-item>SQL</button>
              </li>

              <li class="select-item">
                <button data-select-item>Excel</button>
              </li> -->

            </ul>

          </div>

          <ul class="project-list">

       <li class="project-item  active" data-filter-item data-category="tableau">
              <a href="https://github.com/VinayMeesaraganda/Tableau_Projects/blob/main/HR%20Analytics%20Dashboard.md">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/HR Analytics Dashboard.png" alt="HR Analytics Dashboard" loading="lazy">
                </figure>

                <h3 class="project-title">HR Analytics Dashboard</h3>

                <p class="project-category">Tableau</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="tableau">
              <a href="https://github.com/VinayMeesaraganda/Tableau_Projects/blob/8f54ae0f8999d586b38ee55ff5f2c6bb70d3c3fc/NCAA%20Women%20Statistics.md">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/NCAA Women Statistics.png" alt="NCAA Women Statistics" loading="lazy">
                </figure>

                <h3 class="project-title">NCAA Women Statistics</h3>

                <p class="project-category">Tableau</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="python">
              <a href="https://github.com/VinayMeesaraganda/CS668_Capstone_Project.git">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/Loan Prediction Python.jpg" alt="Loan Prediction using Python" loading="lazy">
                </figure>

                <h3 class="project-title">Loan Default Prediction using Python</h3>

                <p class="project-category">Python</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="tableau">
              <a href="https://github.com/VinayMeesaraganda/Tableau_Projects/blob/main/Loan%20Prediction%20Dashboard%20.md">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/Loan Prediction.png" alt="Loan Prediction Dashboard" loading="lazy">
                </figure>

                <h3 class="project-title">Loan Prediction Dashboard</h3>

                <p class="project-category">Tableau</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="python">
              <a href="https://github.com/VinayMeesaraganda/Python-Projects/tree/main/Employee%20Turnover">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/Employee Turnover.jpg" alt="Employee Turnover Analysis" loading="lazy">
                </figure>

                <h3 class="project-title">Employee Turnover Analysis</h3>

                <p class="project-category">Python</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="python">
              <a href="https://github.com/VinayMeesaraganda/Python-Projects/tree/main/Telecom%20Customer%20Churn">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/telecom churn.png" alt="Telecom Customer Churn Analysis" loading="lazy">
                </figure>

                <h3 class="project-title">Telecom Customer Churn Analysis</h3>

                <p class="project-category">Python</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="tableau">
              <a href="https://github.com/VinayMeesaraganda/Tableau_Projects/blob/main/Gender%20Pay%20Gap%20in%20US%20World%20Cup.md">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/GenderPay.png" alt="Gender Pay Gap in US World Cup" loading="lazy">
                </figure>

                <h3 class="project-title">Gender Pay Gap in US World Cup</h3>

                <p class="project-category">Tableau</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="python">
              <a href="https://github.com/VinayMeesaraganda/Python-Projects/tree/main/Stock%20Prediction">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/Stock Prediction.png" alt="Stock Prediction" loading="lazy">
                </figure>

                <h3 class="project-title">Analysis of Stock Price Trends using Moving Averages</h3>

                <p class="project-category">Python</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="python">
              <a href="https://github.com/VinayMeesaraganda/Python-Projects/tree/main/Temperature%20Device%20Failure">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/Temperature Device Failure.jpg" alt="Temperature Device Failure Analysis" loading="lazy">
                </figure>

                <h3 class="project-title">Temperature Device Failure Analysis</h3>

                <p class="project-category">Python</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="python">
              <a href="https://github.com/VinayMeesaraganda/Python-Projects/tree/main/Indian%20Life%20Expectancy">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/Indian Life Expectancy.jpg" alt="Indian Life Expectancy Analysis" loading="lazy">
                </figure>

                <h3 class="project-title">Indian Life Expectancy Analysis</h3>

                <p class="project-category">Python</p>

              </a>
            </li>

            <li class="project-item  active" data-filter-item data-category="python">
              <a href="https://github.com/VinayMeesaraganda/Python-Projects/tree/main/Patients%20Heart%20Failure%20Analysis">

                <figure class="project-img">
                  <div class="project-item-icon-box">
                    <ion-icon name="eye-outline"></ion-icon>
                  </div>

                  <img src="./assets/images/Heart failure.jpg" alt="Heart Failure Analysis" loading="lazy">
                </figure>

                <h3 class="project-title">Heart Failure Analysis</h3>

                <p class="project-category">Python</p>

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

      <article class="contact" data-page="contact">

        <header>
          <h2 class="h2 article-title">Contact</h2>
        </header>

        <!-- <section class="mapbox" data-mapbox>
          <figure>
            <iframe
              src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d199666.5651251294!2d-121.58334177520186!3d38.56165006739519!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x809ac672b28397f9%3A0x921f6aaa74197fdb!2sSacramento%2C%20CA%2C%20USA!5e0!3m2!1sen!2sbd!4v1647608789441!5m2!1sen!2sbd"
              width="400" height="300" loading="lazy"></iframe>
          </figure>
        </section> -->

        <section class="contact-form">

          <h3 class="h3 form-title">Contact Form</h3>

          <form class="form" method = "post" action="https://formspree.io/f/mbjeprad" data-form>

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

      </article>

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
  <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>

</body>

</html>
