<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Win Moe - CV</title>

  <!-- Font Awesome -->
  <link rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

  <style>
    /* =========================
       A4 PAGE SETTINGS
       ========================= */

    @page {
      size: A4;
      margin: 0;
    }

    * {
      box-sizing: border-box;
    }

    html,
    body {
      margin: 0;
      padding: 0;
      font-family: "Times New Roman", Times, serif;
      color: #222;
      background: #eef3f6;
      -webkit-font-smoothing: antialiased;
    }

    body {
      padding: 20px;
    }

    /* =========================
       MAIN A4 CONTAINER
       ========================= */

    .cv-container {
      width: 210mm;
      min-height: 297mm;
      margin: 0 auto;
    }

    /* =========================
       HEADER
       ========================= */

    .header-container {
      display: flex;
      align-items: center;
      background: linear-gradient(135deg, #0077b6, #00b4d8);
      padding: 25px 30px;
      border-radius: 12px;
      color: white;
      margin-bottom: 15px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.08);
    }

    .profile-photo {
      width: 110px;
      height: 110px;
      flex-shrink: 0;
      object-fit: cover;
      border-radius: 15px;
      border: 3px solid #fff;
      box-shadow: 0 6px 18px rgba(0, 0, 0, 0.15);
    }

    .header-text {
      margin-left: 25px;
    }

    .header-text h1 {
      margin: 0;
      font-size: 32px;
      font-weight: 700;
    }

    .header-text h3 {
      margin: 5px 0 0;
      font-size: 18px;
      font-weight: 500;
      color: #e0f7fa;
    }

    /* =========================
       BODY
       ========================= */

    .cv-body {
      display: flex;
      align-items: stretch;
      background: #fff;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 4px 25px rgba(0, 0, 0, 0.07);
    }

    /* =========================
       SIDEBAR
       ========================= */

    .sidebar {
      width: 34%;
      background: #f8fbfe;
      padding: 24px 21px;
      border-right: 1px solid #e4ebef;
      line-height: 1.45;
    }

    /* =========================
       MAIN CONTENT
       ========================= */

    .main-content {
      width: 66%;
      padding: 24px 28px;
      line-height: 1.45;
    }

    /* =========================
       SECTION TITLES
       ========================= */

    .section-title-side,
    .section-title-main {
      display: flex;
      align-items: center;
      gap: 8px;
      color: #0077b6;
      font-weight: 700;
    }

    .section-title-side {
      font-size: 16px;
      border-bottom: 2px solid #0077b6;
      margin: 21px 0 9px;
      padding-bottom: 5px;
    }

    .section-title-side:first-of-type {
      margin-top: 0;
    }

    .section-title-main {
      font-size: 19px;
      border-bottom: 2px solid #00b4d8;
      margin: 24px 0 10px;
      padding-bottom: 5px;
    }

    .section-title-main:first-of-type {
      margin-top: 0;
    }

    /* =========================
       TEXT
       ========================= */

    p {
      font-size: 13px;
      margin-top: 5px;
      margin-bottom: 7px;
    }

    li {
      font-size: 12.5px;
      margin-bottom: 4px;
    }

    .sidebar p,
    .sidebar li {
      font-size: 12.5px;
    }

    /* =========================
       CARDS
       ========================= */

    .card {
      background: #f9fbfc;
      border-left: 3px solid #0077b6;
      padding: 9px 13px;
      margin: 9px 0;
      border-radius: 0 6px 6px 0;

      break-inside: avoid;
      page-break-inside: avoid;
    }

    .card h4 {
      margin: 0;
      font-size: 15.5px;
      font-weight: 700;
      color: #111;
    }

    .card-meta {
      color: #666;
      margin: 3px 0 6px;
      font-size: 12px;
      font-weight: 500;
    }

    .card ul {
      margin: 3px 0 0;
      padding-left: 18px;
    }

    /* =========================
       LINKS
       ========================= */

    a {
      color: #0077b6;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    /* =========================
       LISTS
       ========================= */

    .sidebar ul {
      padding-left: 19px;
      margin: 0;
    }

    .sidebar ul.no-bullets {
      list-style: none;
      padding-left: 0;
    }

    .sidebar ul.no-bullets li {
      margin: 6px 0;
    }

    /* =========================
       PRINT
       ========================= */

    @media print {

      html,
      body {
        width: 210mm;
        min-height: 297mm;
        background: #fff;
      }

      body {
        padding: 0;
      }

      .cv-container {
        width: 210mm;
        min-height: 297mm;
        margin: 0;
      }

      .header-container,
      .cv-body {
        box-shadow: none;
      }

      a {
        color: inherit;
        text-decoration: none;
      }
    }

    /* =========================
       SCREEN VIEW
       ========================= */

    @media screen and (max-width: 900px) {

      body {
        padding: 10px;
        overflow-x: auto;
      }

      .cv-container {
        width: 210mm;
        margin: 0 auto;
      }
    }

  </style>
</head>

<body>

<div class="cv-container">

  <!-- =========================
       HEADER
       ========================= -->

  <div class="header-container">

    <img
      src="winmoeprofile2.jpg"
      alt="Win Moe Photo"
      class="profile-photo"
    >

    <div class="header-text">
      <h1>Win Moe</h1>
      <h3>English Teacher</h3>
    </div>

  </div>


  <!-- =========================
       CV BODY
       ========================= -->

  <div class="cv-body">


    <!-- =========================
         LEFT SIDEBAR
         ========================= -->

    <aside class="sidebar">


      <!-- CONTACT -->

      <h3 class="section-title-side">
        <i class="fa-solid fa-address-book"></i>
        Contact
      </h3>

      <p><strong>Phone:</strong> 0924854332</p>

      <p>
        <strong>Email:</strong>
        <a href="mailto:minwinmoe123@gmail.com">
          minwinmoe123@gmail.com
        </a>
      </p>

      <p>
        <strong>Address:</strong>
        Chiang Mai, Thailand
      </p>


      <!-- PERSONAL INFORMATION -->

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


      <!-- LANGUAGES -->

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


      <!-- SKILLS -->

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


      <!-- CERTIFICATES -->

      <h3 class="section-title-side">
        <i class="fa-solid fa-certificate"></i>
        Certificates
      </h3>

      <ul>

        <li>TEFL/TESOL (2026)</li>

        <li>
          Teaching English to Young Learners (2026)
        </li>

        <li>
          Teaching English to Refugee and Displaced Learners
        </li>

        <li>
          English for Career Development
        </li>

        <li>
          English for Tourism Professionals
        </li>

        <li>
          Teaching English Academic Writing
        </li>

        <li>
          Creating and Implementing Online Courses
        </li>

        <li>
          Teaching English: How to Teach Pronunciation
        </li>

        <li>
          Teaching English: Assessing Learning
        </li>

        <li>
          Teaching English: How to Adapt Resources
        </li>

        <li>
          Exploring Learning Disabilities
        </li>

        <li>
          English Four Skills (2018)
        </li>

        <li>
          Introduction to Social Sciences
        </li>

        <li>
          Diversity and Inclusion in the Workplace
        </li>

        <li>
          Teaching Online
        </li>

        <li>
          I-Office Computer (2019)
        </li>

        <li>
          Google Digital Marketing &amp; E-Commerce (2025)
        </li>

        <li>
          Career Advancement (2024)
        </li>

        <li>
          Mastering E-Learning Designs for Modern Educators (2025)
        </li>

        <li>
          Stress Management and Self-Care (2025)
        </li>

      </ul>


      <!-- VOLUNTEER EXPERIENCE -->

      <h3 class="section-title-side">
        <i class="fa-solid fa-hands-helping"></i>
        Volunteer Experience
      </h3>

      <ul>

        <li>
          <strong>Volunteer English Teacher:</strong>
          Dahrah Learning Center, Myanmar (2024)
        </li>

        <li>
          <strong>Volunteer Content Creator &amp; Presenter:</strong>
          Payap University, Chiang Mai, Thailand (2025)
        </li>

        <li>
          <strong>Volunteer ESL Instructor (Four Skills):</strong>
          Poy English Program, Myanmar (2025)
        </li>

        <li>
          <strong>Cultural Exchange Volunteer:</strong>
          International College, Payap University, Thailand (2024)
        </li>

      </ul>

    </aside>


    <!-- =========================
         RIGHT MAIN CONTENT
         ========================= -->

    <main class="main-content">


      <!-- CAREER OBJECTIVE -->

      <h3 class="section-title-main">
        <i class="fa-solid fa-bullseye"></i>
        Career Objective
      </h3>

      <p style="text-align: justify; color:#444;">

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


      <!-- WORK EXPERIENCE -->

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


      <!-- EDUCATION -->

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
          3rd Year |
          Expected Graduation: 2027
        </div>

      </div>


      <div class="card">

        <h4>
          Diploma in Social Sciences
        </h4>

        <div class="card-meta">
          National University of Zoland, Myanmar |
          2025–Present |
          Expected Graduation: July 2026
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
          English (Upper Intermediate) &amp; I-Office Computer Certificate
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
          2nd Year | 2018–2020
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


      <!-- PORTFOLIO -->

      <h3 class="section-title-main">
        <i class="fa-solid fa-briefcase-clock"></i>
        Portfolio
      </h3>

      <div class="card">

        <p style="margin:0;">

          <a
            href="https://winmoe0.github.io/winmoe.portfolio/"
            target="_blank"
            rel="noopener noreferrer"
          >
            winmoe0.github.io/winmoe.portfolio/
          </a>

        </p>

      </div>


      <!-- LINKEDIN -->

      <h3 class="section-title-main">
        <i class="fa-brands fa-linkedin"></i>
        LinkedIn
      </h3>

      <div class="card">

        <p style="margin:0;">

          <a
            href="https://www.linkedin.com/in/win-moe-73b006395"
            target="_blank"
            rel="noopener noreferrer"
          >
            linkedin.com/in/win-moe-73b006395
          </a>

        </p>

      </div>


      <!-- REFERENCES -->

      <h3 class="section-title-main">
        <i class="fa-solid fa-file-signature"></i>
        References
      </h3>

      <div
        class="card"
        style="border-left-color:#aaa;"
      >

        <p style="margin:0; color:#555; font-style:italic;">
          References available upon request.
        </p>

      </div>


    </main>

  </div>

</div>
