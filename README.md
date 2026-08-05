
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=1200, initial-scale=1.0">
  <title>Win Moe - CV</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">
  <!-- Font Awesome for clean, professional icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    body {
      margin: 0;
      padding: 40px 20px;
      background-color: #f4f7f9;
      -webkit-font-smoothing: antialiased;
      font-family: 'Poppins', sans-serif;
    }
    .cv-container {
      max-width: 1000px;
      margin: 0 auto;
    }
    .header-container {
      display: flex;
      align-items: center;
      justify-content: flex-start;
      background: linear-gradient(135deg, #0077b6, #00b4d8);
      padding: 40px;
      border-radius: 16px;
      color: white;
      margin-bottom: 25px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.05);
    }
    .header-text {
      margin-left: 30px;
    }
    .header-text h1 {
      margin: 0;
      font-size: 2.8em;
      font-weight: 700;
      letter-spacing: -0.5px;
    }
    .header-text h3 {
      margin: 8px 0 0 0;
      font-weight: 500;
      color: #e0f7fa;
      letter-spacing: 0.5px;
    }
    .cv-body {
      display: flex;
      flex-wrap: wrap;
      box-shadow: 0 4px 25px rgba(0,0,0,0.05);
      border-radius: 16px;
      overflow: hidden;
      background: #fff;
    }
    .sidebar {
      flex: 1;
      min-width: 280px;
      background: #f8fbfe;
      padding: 35px 30px;
      border-right: 1px solid #eef2f5;
      line-height: 1.6;
    }
    .main-content {
      flex: 2;
      min-width: 320px;
      padding: 35px 40px;
      line-height: 1.6;
    }
    .section-title-side {
      color: #0077b6;
      border-bottom: 2px solid #0077b6;
      margin-top: 30px;
      padding-bottom: 6px;
      font-size: 1.15em;
      display: flex;
      align-items: center;
      gap: 10px;
    }
    .section-title-side:first-of-type {
      margin-top: 0;
    }
    .section-title-main {
      color: #0077b6;
      border-bottom: 3px solid #00b4d8;
      padding-bottom: 6px;
      margin-top: 35px;
      font-size: 1.3em;
      display: flex;
      align-items: center;
      gap: 10px;
    }
    .section-title-main:first-of-type {
      margin-top: 0;
    }
    .card {
      background: #f9fbfc;
      border-left: 4px solid #0077b6;
      padding: 14px 18px;
      margin: 15px 0;
      border-radius: 0 8px 8px 0;
    }
    .card h4 {
      margin: 0;
      font-size: 1.1em;
      color: #111;
    }
    .card-meta {
      color: #666;
      margin: 4px 0 8px;
      font-size: 0.9em;
      font-weight: 500;
    }
    a {
      color: #0077b6;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }

    /* Responsive adjustments */
    @media (max-width: 768px) {
      body {
        padding: 15px;
      }
      .header-container {
        flex-direction: column;
        text-align: center;
        padding: 30px 20px;
      }
      .header-text {
        margin-left: 0;
        margin-top: 20px;
      }
      .cv-body {
        flex-direction: column;
      }
      .sidebar {
        border-right: none;
        border-bottom: 1px solid #eef2f5;
        padding: 30px 20px;
      }
      .main-content {
        padding: 30px 20px;
      }
    }
  </style>
</head>
<body>

<div class="cv-container">

  <!-- Header Section -->
  <div class="header-container">
    <div style="flex-shrink:0;">
      <img src="winmoeprofile2.jpg" alt="Win Moe Photo" width="140" height="140" style="border-radius:20px; border:4px solid #fff; box-shadow:0 8px 25px rgba(0,0,0,0.15); display: block; object-fit: cover;">
    </div>
    <div class="header-text">
      <h1>Win Moe</h1>
      <h3>English Teacher</h3>
    </div>
  </div>

  <!-- Main Body Wrapper -->
  <div class="cv-body">

    <!-- Left Sidebar Content -->
    <div class="sidebar">
      <h3 class="section-title-side"><i class="fa-solid fa-address-book"></i> Contact</h3>
      <p style="margin: 8px 0;"><b>Phone:</b> 0924854332</p>
      <p style="margin: 8px 0;"><b>Email:</b> <a href="mailto:minwinmoe123@gmail.com" style="word-break: break-all;">minwinmoe123@gmail.com</a></p>
      <p style="margin: 8px 0;"><b>Address:</b> Chiang Mai, Thailand</p>

      <h3 class="section-title-side"><i class="fa-solid fa-user"></i> Personal Info</h3>
      <ul style="list-style:none; padding:0; margin: 0;">
        <li style="margin: 8px 0;"><b>Gender:</b> Male</li>
        <li style="margin: 8px 0;"><b>Age:</b> 28</li>
        <li style="margin: 8px 0;"><b>Nationality:</b> Myanmar</li>
        <li style="margin: 8px 0;"><b>Marital Status:</b> Single</li>
      </ul>

      <h3 class="section-title-side"><i class="fa-solid fa-earth-americas"></i> Languages</h3>
      <ul style="padding-left:20px; margin: 0;">
        <li style="margin: 6px 0;">Mon (Native)</li>
        <li style="margin: 6px 0;">Burmese (Fluent)</li>
        <li style="margin: 6px 0;">English (Advanced)</li>
        <li style="margin: 6px 0;">Thai (Conversational)</li>
      </ul>

      <h3 class="section-title-side"><i class="fa-solid fa-star"></i> Skills</h3>
      <ul style="padding-left:20px; margin: 0;">
        <li style="margin: 6px 0;">Excellent Communication</li>
        <li style="margin: 6px 0;">Content Creation</li>
        <li style="margin: 6px 0;">Video Editing</li>
        <li style="margin: 6px 0;">Photography & Videography</li>
        <li style="margin: 6px 0;">Time Management</li>
        <li style="margin: 6px 0;">Flexibility & Adaptability</li>
        <li style="margin: 6px 0;">Self-Management</li>
        <li style="margin: 6px 0;">Presentation Skills</li>
        <li style="margin: 6px 0;">Team Collaboration</li>
        <li style="margin: 6px 0;">Patience & Understanding</li>
      </ul>

      <h3 class="section-title-side"><i class="fa-solid fa-certificate"></i> Certificates</h3>
      <ul style="padding-left:20px; margin: 0; font-size: 0.95em;">
        <li style="margin: 6px 0;">TEFL/TESOL (2026)</li>
        <li style="margin: 6px 0;">Teaching English to Young Learners (2026)</li>
        <li style="margin: 6px 0;">Teaching English to Refugee and Displaced Learners</li>
        <li style="margin: 6px 0;">English for Career Development</li>
        <li style="margin: 6px 0;">English for Tourism Professionals </li>
        <li style="margin: 6px 0;">Teaching English Academic Writing </li>
        <li style="margin: 6px 0;">Creating and Implementing Online Courses </li>
        <li style="margin: 6px 0;">Teaching English: How to Teach Pronunciation</li>
        <li style="margin: 6px 0;">Teaching English: Assessing Learning</li>
        <li style="margin: 6px 0;">Teaching English: How to Adapt Resources</li>
        <li style="margin: 6px 0;">Exploring Learning Disabilities</li>
        <li style="margin: 6px 0;">English Four Skills (2018)</li>
        <li style="margin: 6px 0;">Introduction to Social Sciences</li>
        <li style="margin: 6px 0;">Diversity and Inclusion in the Workplace</li>
        <li style="margin: 6px 0;">Teaching Online</li>
        <li style="margin: 6px 0;">I-Office Computer (2019)</li>
        <li style="margin: 6px 0;">Google Digital Marketing & E-Commerce (2025)</li>
        <li style="margin: 6px 0;">Career Advancement (2024)</li>
        <li style="margin: 6px 0;">Mastering E-Learning Designs for Modern Educators (2025)</li>
        <li style="margin: 6px 0;">Stress Management and Self-Care (2025)</li>
        <li style="margin: 6px 0;">Localization in Humanitarian Aid (2025)</li>
        <li style="margin: 6px 0;">Financial Literacy (2018)</li>
      </ul>

      <h3 class="section-title-side"><i class="fa-solid fa-hands-helping"></i> Volunteer Experience</h3>
      <ul style="padding-left:20px; margin: 0; font-size: 0.95em;">
        <li style="margin: 8px 0;"><b>Volunteer English Teacher:</b> Dahrah Learning Center, Myanmar (2024)</li>
        <li style="margin: 8px 0;"><b>Volunteer Content Creator & Presenter:</b> Payap University, Chiang Mai, Thailand (2025)</li>
        <li style="margin: 8px 0;"><b>Volunteer ESL Instructor (Four Skills):</b> Poy English Program, Myanmar (2025)</li>
        <li style="margin: 8px 0;"><b>Cultural Exchange Volunteer:</b> International College, Payap University, Thailand (2024)</li>
      </ul>
    </div>

    <!-- Right Main Content -->
    <div class="main-content">
      <h3 class="section-title-main"><i class="fa-solid fa-bullseye"></i> Career Objective</h3>
      <p style="color: #444; text-align: justify; margin: 10px 0 25px 0;">Motivated and compassionate English educator with over four years of teaching experience, both onsite and online, committed to fostering an inclusive, engaging, and inspiring learning environment. Passionate about empowering students to achieve their full potential through interactive teaching methods, cultural awareness, and personalized guidance. Skilled in curriculum development, classroom management, and innovative instructional strategies that enhance language proficiency, critical thinking, and confidence. Dedicated to lifelong learning and continuous professional growth, with a strong desire to make a positive impact on students’ academic and personal development.</p>

      <h3 class="section-title-main"><i class="fa-solid fa-briefcase"></i> Work Experience</h3>

      <div class="card">
        <h4>English Teacher</h4>
        <div class="card-meta">Mon National Primary School, Ye Township, Myanmar | 2023–2024</div>
        <ul style="margin:0; padding-left:18px; color: #444;">
          <li>Improved student English proficiency across core language pillars: writing, reading, listening, and speaking.</li>
          <li>Implemented creative, student-centered instructional methods to drive engagement.</li>
        </ul>
      </div>

      <div class="card">
        <h4>Content Creator</h4>
        <div class="card-meta">Online Educational Platforms | 2019–Present</div>
        <ul style="margin:0; padding-left:18px; color: #444;">
          <li>Produced high-quality educational English videos reaching highly diverse student demographics.</li>
          <li>Cultivated and maintained digital networks to foster supportive online learning environments.</li>
        </ul>
      </div>

      <div class="card">
        <h4>Online English Instructor</h4>
        <div class="card-meta">Poy English Program | 2019–Present</div>
        <ul style="margin:0; padding-left:18px; color: #444;">
          <li>Delivered dynamic online modules leveraging integrated interactive media platforms.</li>
          <li>Provided personalized guidance to help students correct pronunciation, polish writing, and scale spoken communication.</li>
        </ul>
      </div>

      <div class="card">
        <h4>Leadership Experience as Chairman</h4>
        <div class="card-meta">G60-99 Mon Charity Group | 2020–2024</div>
        <ul style="margin:0; padding-left:18px; color: #444;">
          <li>Headed community service initiatives and drove logistical strategy to support local community welfare.</li>
          <li>Facilitated cross-functional team communication to execute high-impact outreach programs.</li>
        </ul>
      </div>

      <h3 class="section-title-main"><i class="fa-solid fa-graduation-cap"></i> Education</h3>

      <div class="card">
        <h4>Bachelor of Arts in English Communication</h4>
        <div class="card-meta">Payap University, Chiang Mai, Thailand | 3rd Year (Expected Graduation: 2027)</div>
      </div>

      <div class="card">
        <h4>Diploma in Social Sciences</h4>
        <div class="card-meta">National University of Zoland, Myanmar | 2025–Present (Expected Graduation: July 2026)</div>
      </div>

      <div class="card">
        <h4>Associate Degree in Education (Teaching)</h4>
        <div class="card-meta">Mon National College, Myanmar | 2022–2024</div>
      </div>

      <div class="card">
        <h4>English (Upper Intermediate) & I-Office Computer Certificate</h4>
        <div class="card-meta">BopHtaw, MNEC | 2021–2022</div>
      </div>

      <div class="card">
        <h4>Undergraduate Coursework in Mathematics</h4>
        <div class="card-meta">Hpa-An University, Myanmar | 2nd Year, 2019–2020</div>
      </div>
      
      <div class="card">
        <h4>English Four Skills Program</h4>
        <div class="card-meta">Dahrah Learning Center, Mawlamyine, Myanmar | 2018–2019</div>
      </div>

      <!-- Portfolio Section -->
      <h3 class="section-title-main"><i class="fa-solid fa-briefcase-clock"></i> Portfolio</h3>
      <div class="card">
        <p style="margin:0;">
          <a href="https://winmoe0.github.io/winmoe.portfolio/" target="_blank" style="font-weight: 500; word-break: break-all;">
            winmoe0.github.io/winmoe.portfolio/
          </a>
        </p>
      </div>

      <!-- LinkedIn Section -->
      <h3 class="section-title-main"><i class="fa-brands fa-linkedin"></i> LinkedIn</h3>
      <div class="card">
        <p style="margin:0;">
          <a href="https://www.linkedin.com/in/win-moe-73b006395" target="_blank" style="font-weight: 500; word-break: break-all;">
            linkedin.com/in/win-moe-73b006395
          </a>
        </p>
      </div>

      <!-- References Section -->
      <h3 class="section-title-main"><i class="fa-solid fa-file-signature"></i> References</h3>
      <div class="card" style="border-left-color: #aaa;">
        <p style="margin:0; color:#555; font-style: italic;">References available upon request.</p>
      </div>

    </div>
  </div>
</div>
