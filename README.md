
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=1200, initial-scale=1.0">
  <title>Win Moe - CV</title>

  <link rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

  <style>
    /* ================================
       A4 PAGE SETTINGS
       ================================ */

    @page {
      size: 8.27in 11.69in;
      margin: 0;
    }

    * {
      box-sizing: border-box;
    }

    html,
    body {
      margin: 0;
      padding: 0;
      background: #eef2f5;
      font-family: "Times New Roman", Times, serif;
      color: #222;
    }

    body {
      -webkit-font-smoothing: antialiased;
    }

    /* Exact A4 dimensions:
       8.27 × 11.69 inches
       210 × 297 mm
    */

    .cv-container {
      width: 8.27in;
      min-height: 11.69in;
      margin: 25px auto;
      background: #ffffff;
      overflow: hidden;
      box-shadow: 0 5px 25px rgba(0, 0, 0, 0.10);
    }

    /* ================================
       HEADER
       ================================ */

    .header-container {
      display: flex;
      align-items: center;
      background: linear-gradient(135deg, #0077b6, #00a6d6);
      padding: 24px 28px;
      color: white;
    }

    .profile-photo {
      width: 105px;
      height: 105px;
      flex-shrink: 0;
      object-fit: cover;
      border-radius: 14px;
      border: 3px solid #ffffff;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.15);
    }

    .header-text {
      margin-left: 24px;
    }

    .header-text h1 {
      margin: 0;
      font-size: 31px;
      line-height: 1.1;
      font-weight: 700;
      letter-spacing: 0.2px;
    }

    .header-text h3 {
      margin: 7px 0 0;
      font-size: 17px;
      font-weight: 400;
      color: #e8faff;
    }

    /* ================================
       MAIN BODY
       ================================ */

    .cv-body {
      display: grid;
      grid-template-columns: 34% 66%;
      min-height: calc(11.69in - 153px);
    }

    /* ================================
       SIDEBAR
       ================================ */

    .sidebar {
      background: #f6fafc;
      padding: 22px 20px;
      border-right: 1px solid #e4edf2;
      font-size: 11px;
      line-height: 1.42;
    }

    /* ================================
       MAIN CONTENT
       ================================ */

    .main-content {
      padding: 22px 25px;
      font-size: 11.5px;
      line-height: 1.42;
    }

    /* ================================
       SECTION HEADINGS
       ================================ */

    .section-title-side,
    .section-title-main {
      display: flex;
      align-items: center;
      gap: 7px;
      color: #0077b6;
      font-weight: 700;
    }

    .section-title-side {
      font-size: 13px;
      border-bottom: 1.5px solid #0077b6;
      padding-bottom: 4px;
      margin: 18px 0 8px;
    }

    .section-title-side:first-child {
      margin-top: 0;
    }

    .section-title-main {
      font-size: 16px;
      border-bottom: 2px solid #00a6d6;
      padding-bottom: 4px;
      margin: 18px 0 8px;
    }

    .section-title-main:first-child {
      margin-top: 0;
    }

    /* ================================
       CONTACT / PERSONAL INFO
       ================================ */

    .sidebar p {
      margin: 5px 0;
    }

    .sidebar ul {
      margin: 0;
      padding-left: 17px;
    }

    .sidebar ul.no-bullets {
      padding-left: 0;
      list-style: none;
    }

    .sidebar li {
      margin: 4px 0;
    }

    /* ================================
       CARDS
       ================================ */

    .card {
      background: #f9fbfc;
      border-left: 3px solid #0077b6;
      padding: 8px 11px;
      margin: 8px 0;
      border-radius: 0 5px 5px 0;
    }

    .card h4 {
      margin: 0;
      color: #111;
      font-size: 13px;
      line-height: 1.2;
      font-weight: 700;
    }

    .card-meta {
      margin: 3px 0 5px;
      color: #666;
      font-size: 10px;
      line-height: 1.25;
      font-weight: 400;
    }

    .card ul {
      margin: 0;
      padding-left: 16px;
      color: #444;
    }

    .card li {
      margin: 2px 0;
    }

    /* ================================
       GENERAL TEXT
       ================================ */

    .objective {
      margin: 6px 0 12px;
      color: #444;
      text-align: justify;
      line-height: 1.42;
    }

    a {
      color: #0077b6;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    .small-text {
      font-size: 10px;
    }

    /* ================================
       PRINT
       ================================ */

    @media print {

      html,
      body {
        width: 8.27in;
        height: 11.69in;
        margin: 0;
        padding: 0;
        background: #ffffff;
      }

      .cv-container {
        width: 8.27in;
        height: 11.69in;
        min-height: 11.69in;
        margin: 0;
        box-shadow: none;
        overflow: hidden;
      }

      .header-container {
        print-color-adjust: exact;
        -webkit-print-color-adjust: exact;
      }

      .sidebar {
        print-color-adjust: exact;
        -webkit-print-color-adjust: exact;
      }

      .card {
        break-inside: avoid;
        page-break-inside: avoid;
      }

      a {
        color: #0077b6;
      }
    }

    /* ================================
       SCREEN RESPONSIVENESS
       ================================ */

    @media screen and (max-width: 900px) {

      body {
        padding: 10px;
      }

      .cv-container {
        width: 100%;
        min-height: auto;
        margin: 0 auto;
      }
    }

    @media screen and (max-width: 650px) {

      .header-container {
        padding: 22px;
      }

      .profile-photo {
        width: 85px;
        height: 85px;
      }

      .header-text {
        margin-left: 16px;
      }

      .header-text h1 {
        font-size: 25px;
      }

      .header-text h3 {
        font-size: 14px;
      }

      .cv-body {
        grid-template-columns: 1fr;
      }

      .sidebar {
        border-right: none;
        border-bottom: 1px solid #e4edf2;
      }
    }
  </style>
</head>

<body>

<div class="cv-container">

  <!-- ================================
       HEADER
       ================================ -->

  <header class="header-container">

    <img
      src="winmoeprofile2.jpg"
      alt="Win Moe Profile Photo"
      class="profile-photo"
    >

    <div class="header-text">
      <h1>Win Moe</h1>
      <h3>English Teacher</h3>
    </div>

  </header>


  <!-- ================================
       CV BODY
       ================================ -->

  <div class="cv-body">


    <!-- ================================
         SIDEBAR
         ================================ -->

    <aside class="sidebar">

      <!-- Contact -->

      <h3 class="section-title-side">
        <i class="fa-solid fa-address-book"></i>
        Contact
      </h3>

      <p>
        <strong>Phone:</strong> 0924854332
      </p>

      <p>
        <strong>Email:</strong>
        <a href="mailto:minwinmoe123@gmail.com">
          minwinmoe123@gmail.com
        </a>
      </p>

      <p>
        <strong>Address:</strong> Chiang Mai, Thailand
      </p>


      <!-- Personal Information -->

      <h3 class="section-title-side">
        <i class="fa-solid fa-user"></i>
        Personal Information
      </h3>

      <ul class="no-bullets">

        <li>
          <strong>Gender:</strong> Male
        </li>

        <li>
          <strong>Age:</strong> 28
        </li>

        <li>
          <strong>Nationality:</strong> Myanmar
        </li>

        <li>
          <strong>Marital Status:</strong> Single
        </li>

      </ul>


      <!-- Languages -->

      <h3 class="section-title-side">
        <i class="fa-solid fa-earth-americas"></i>
        Languages
      </h3>

      <ul>

        <li>Mon (Native)</li>
        <li>Burmese (Fluent)</li>
        <li>English (Advanced)</li>
        <li>Thai (Conversational)</li>

      </ul>


      <!-- Skills -->

      <h3 class="section-title-side">
        <i class="fa-solid fa-star"></i>
        Skills
      </h3>

      <ul>

        <li>Lesson Planning and Instruction</li>
        <li>Classroom Management</li>
        <li>Student Assessment and Feedback</li>
        <li>Team Collaboration</li>
        <li>Effective Communication</li>
        <li>Time Management</li>
        <li>Flexibility and Adaptability</li>
        <li>Content Creation and Videography</li>
        <li>Social Media Management</li>

      </ul>


      <!-- Certificates -->

      <h3 class="section-title-side">
        <i class="fa-solid fa-certificate"></i>
        Certificates
      </h3>

      <ul class="small-text">

        <li>TEFL/TESOL (2026)</li>

        <li>
          Teaching English to Young Learners (2026)
        </li>

        <li>
          Teaching English to Refugee and Displaced Learners
        </li>

        <li>English for Career Development</li>

        <li>English for Tourism Professionals</li>

        <li>Teaching English Academic Writing</li>

        <li>Creating and Implementing Online Courses</li>

        <li>
          Teaching English: How to Teach Pronunciation
        </li>

        <li>
          Teaching English: Assessing Learning
        </li>

        <li>
          Teaching English: How to Adapt Resources
        </li>

        <li>Exploring Learning Disabilities</li>

        <li>English Four Skills (2018)</li>

        <li>Introduction to Social Sciences</li>

        <li>Diversity and Inclusion in the Workplace</li>

        <li>Teaching Online</li>

        <li>I-Office Computer (2019)</li>

        <li>
          Google Digital Marketing &amp; E-Commerce (2025)
        </li>

        <li>Career Advancement (2024)</li>

        <li>
          Mastering E-Learning Designs for Modern Educators (2025)
        </li>

        <li>
          Stress Management and Self-Care (2025)
        </li>

      </ul>


      <!-- Volunteer Experience -->

      <h3 class="section-title-side">
        <i class="fa-solid fa-hands-helping"></i>
        Volunteer Experience
      </h3>

      <ul class="small-text">

        <li>
          <strong>Volunteer English Teacher:</strong>
          Dahrah Learning Center, Myanmar (2024)
        </li>

        <li>
          <strong>Volunteer Content Creator &amp; Presenter:</strong>
          Payap University, Chiang Mai, Thailand (2025)
        </li>

        <li>
          <strong>Volunteer ESL Instructor:</strong>
          Poy English Program, Myanmar (2025)
        </li>

        <li>
          <strong>Cultural Exchange Volunteer:</strong>
          International College, Payap University, Thailand (2024)
        </li>

      </ul>

    </aside>


    <!-- ================================
         MAIN CONTENT
         ================================ -->

    <main class="main-content">


      <!-- Career Objective -->

      <h3 class="section-title-main">
        <i class="fa-solid fa-bullseye"></i>
        Career Objective
      </h3>

      <p class="objective">
        Motivated and compassionate English educator with over four years
        of teaching experience in both onsite and online settings.
        Experienced in student-centered instruction, lesson planning,
        classroom management, assessment, and digital learning.
        Committed to creating inclusive and engaging learning environments
        that help students develop English proficiency, confidence, and
        critical thinking skills. Passionate about continuous professional
        development and contributing positively to students' academic and
        personal growth.
      </p>


      <!-- Work Experience -->

      <h3 class="section-title-main">
        <i class="fa-solid fa-briefcase"></i>
        Work Experience
      </h3>


      <div class="card">

        <h4>English Teacher</h4>

        <div class="card-meta">
          Mon National Primary School, Ye Township, Myanmar | 2023–2024
        </div>

        <ul>

          <li>
            Improved students' English proficiency in reading, writing,
            listening, and speaking.
          </li>

          <li>
            Implemented creative and student-centered teaching methods
            to increase participation and engagement.
          </li>

        </ul>

      </div>


      <div class="card">

        <h4>Content Creator</h4>

        <div class="card-meta">
          Online Educational Platforms | 2019–Present
        </div>

        <ul>

          <li>
            Created educational English content for diverse learners
            through online platforms.
          </li>

          <li>
            Developed digital learning materials and maintained online
            communities to support English language learning.
          </li>

        </ul>

      </div>


      <div class="card">

        <h4>Online English Instructor</h4>

        <div class="card-meta">
          Poy English Program | 2019–2026
        </div>

        <ul>

          <li>
            Delivered interactive online English lessons using digital
            learning platforms and multimedia resources.
          </li>

          <li>
            Provided individualized feedback on pronunciation, writing,
            and spoken communication.
          </li>

        </ul>

      </div>


      <div class="card">

        <h4>Chairman – Leadership &amp; Community Service</h4>

        <div class="card-meta">
          G60-99 Mon Charity Group | 2020–2022
        </div>

        <ul>

          <li>
            Led community service and fundraising initiatives supporting
            local community welfare.
          </li>

          <li>
            Coordinated volunteers, delegated responsibilities, and
            facilitated effective team communication.
          </li>

        </ul>

      </div>


      <!-- Education -->

      <h3 class="section-title-main">
        <i class="fa-solid fa-graduation-cap"></i>
        Education
      </h3>


      <div class="card">

        <h4>
          Bachelor of Arts in English Communication
        </h4>

        <div class="card-meta">
          Payap University, Chiang Mai, Thailand |
          Expected Graduation: 2027
        </div>

      </div>


      <div class="card">

        <h4>
          Diploma in Social Sciences
        </h4>

        <div class="card-meta">
          National University of Zoland, Myanmar |
          Completed July 2026
        </div>

      </div>


      <div class="card">

        <h4>
          Associate Degree in Education (Teaching)
        </h4>

        <div class="card-meta">
          Mon National College, Myanmar | 2022–2024
        </div>

      </div>


      <div class="card">

        <h4>
          English (Upper Intermediate) &amp;
          I-Office Computer Certificate
        </h4>

        <div class="card-meta">
          BopHtaw, MNEC | 2021–2022
        </div>

      </div>


      <div class="card">

        <h4>
          Undergraduate Coursework in Mathematics
        </h4>

        <div class="card-meta">
          Hpa-An University, Myanmar |
          2nd Year, 2018–2020
        </div>

      </div>


      <div class="card">

        <h4>
          English Four Skills Program
        </h4>

        <div class="card-meta">
          Dahrah Learning Center, Mawlamyine, Myanmar |
          2018–2019
        </div>

      </div>


      <!-- Portfolio -->

      <h3 class="section-title-main">
        <i class="fa-solid fa-briefcase-clock"></i>
        Portfolio
      </h3>

      <div class="card">

        <a
          href="https://winmoe0.github.io/winmoe.portfolio/"
          target="_blank"
          rel="noopener noreferrer"
        >
          winmoe0.github.io/winmoe.portfolio/
        </a>

      </div>


      <!-- LinkedIn -->

      <h3 class="section-title-main">
        <i class="fa-brands fa-linkedin"></i>
        LinkedIn
      </h3>

      <div class="card">

        <a
          href="https://www.linkedin.com/in/win-moe-73b006395"
          target="_blank"
          rel="noopener noreferrer"
        >
          linkedin.com/in/win-moe-73b006395
        </a>

      </div>


      <!-- References -->

      <h3 class="section-title-main">
        <i class="fa-solid fa-file-signature"></i>
        References
      </h3>

      <div class="card" style="border-left-color:#aaa;">

        <p style="margin:0; color:#555; font-style:italic;">
          References available upon request.
        </p>

      </div>

    </main>

  </div>

</div>
