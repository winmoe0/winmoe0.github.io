<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="robots" content="noindex">
  <title>Win Moe - Professional CV</title>

  <!-- Fonts & Icons -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

  <style>
    /* ===== Global ===== */
    body {
      font-family: 'Poppins', sans-serif;
      background: #f4f6f8;
      margin: 0;
      padding: 40px;
      color: #333;
    }

    .cv-wrapper {
      max-width: 1000px;
      margin: 0 auto;
      background: #fff;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
      border-radius: 16px;
      overflow: hidden;
      display: flex;
      flex-direction: column;
    }

    /* ===== Header ===== */
    .header {
      background: linear-gradient(135deg, #0077b6, #00b4d8);
      color: #fff;
      text-align: center;
      padding: 50px 20px;
      position: relative;
    }

    .header img {
      width: 130px;
      height: 130px;
      border-radius: 50%;
      border: 5px solid #fff;
      object-fit: cover;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
      margin-bottom: 15px;
    }

    .header h1 {
      font-size: 2.2em;
      margin: 10px 0 5px;
      letter-spacing: 1px;
      font-weight: 700;
    }

    .header h2 {
      font-size: 1.1em;
      font-weight: 400;
      color: #e0f7fa;
      letter-spacing: 1px;
    }

    /* ===== Body Layout ===== */
    .main {
      display: flex;
      flex-wrap: wrap;
    }

    .sidebar {
      background: #f1f7fa;
      flex: 1;
      padding: 30px 25px;
      border-right: 1px solid #e0e0e0;
    }

    .content {
      flex: 2;
      padding: 30px 40px;
    }

    /* ===== Sidebar Sections ===== */
    .sidebar h3 {
      font-size: 1.1em;
      color: #0077b6;
      text-transform: uppercase;
      border-bottom: 2px solid #0077b6;
      padding-bottom: 5px;
      margin-bottom: 15px;
    }

    .sidebar p, .sidebar li {
      font-size: 0.9em;
      margin: 6px 0;
    }

    .sidebar i {
      color: #0077b6;
      margin-right: 8px;
    }

    .sidebar ul {
      list-style: none;
      padding: 0;
    }

    .sidebar ul li::before {
      content: "• ";
      color: #0077b6;
    }

    a {
      color: #0077b6;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    /* ===== Content Sections ===== */
    .content section {
      margin-bottom: 35px;
    }

    .content h3 {
      color: #0077b6;
      font-size: 1.3em;
      text-transform: uppercase;
      border-bottom: 3px solid #00b4d8;
      display: inline-block;
      padding-bottom: 3px;
      margin-bottom: 15px;
    }

    .entry {
      margin-bottom: 20px;
      background: #f9fbfc;
      padding: 15px 20px;
      border-left: 4px solid #0077b6;
      border-radius: 8px;
      transition: all 0.3s ease;
    }

    .entry:hover {
      background: #e8f6fb;
    }

    .entry h4 {
      margin: 0 0 5px;
      font-size: 1.1em;
      color: #222;
      font-weight: 600;
    }

.entry .meta {
  font-size: 0.9em;
  color: #777;
  margin-bottom: 8px;
  font-weight: 300; /* make it lighter / remove bold */
}

    .entry .meta {
      font-size: 0.9em;
      color: #777;
      margin-bottom: 8px;
    }

    .entry ul {
      margin: 0;
      padding-left: 20px;
      font-size: 0.95em;
    }

    .entry li {
      margin-bottom: 5px;
    }

    /* ===== Print ===== */
    @media print {
      body { padding: 0; background: #fff; }
      .cv-wrapper { box-shadow: none; }
      .header { background: #0077b6; color: #fff; }
      .sidebar { background: #f1f7fa; color: #000; }
    }

    /* ===== Mobile ===== */
    @media (max-width: 768px) {
      .main { flex-direction: column; }
      .sidebar, .content { padding: 20px; }
      .header h1 { font-size: 1.8em; }
    }
  </style>
  
</head>
<header class="header">
  <div class="header-left">
    <img src="wmcvphoto.jpg" alt="Win Moe Photo">
  </div>
  <div class="header-right">
    <h1>Win Moe</h1>
    <h2>English Teacher</h2>
  </div>
</header>

<style>
  .header {
    display: flex;
    align-items: center;
    justify-content: flex-start;
    padding: 50px 40px;
    background: linear-gradient(135deg, #0077b6, #00b4d8);
    position: relative;
    overflow: hidden;
  }

  /* Decorative shapes in background */
  .header::before {
    content: "";
    position: absolute;
    top: -50px;
    right: -50px;
    width: 200px;
    height: 200px;
    background: rgba(255,255,255,0.1);
    border-radius: 50%;
    transform: rotate(45deg);
  }
  .header::after {
    content: "";
    position: absolute;
    bottom: -60px;
    left: -60px;
    width: 150px;
    height: 150px;
    background: rgba(255,255,255,0.08);
    border-radius: 50%;
    transform: rotate(-30deg);
  }

  .header-left img {
    width: 150px;
    height: 150px;
    border-radius: 20px;
    object-fit: cover;
    border: 4px solid #fff;
    box-shadow: 0 8px 25px rgba(0,0,0,0.2);
    transition: transform 0.3s ease;
  }

  .header-left img:hover {
    transform: scale(1.05) rotate(2deg);
  }

  .header-right {
    margin-left: 30px;
  }

  .header-right h1 {
    font-size: 2.5em;
    color: #fff;
    font-weight: 700;
    margin: 0;
    background: linear-gradient(90deg, #ffe066, #ff6b6b);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  }

  .header-right h2 {
    font-size: 1.2em;
    color: #e0f7fa;
    margin-top: 8px;
    letter-spacing: 1px;
    font-weight: 500;
  }

  /* Responsive */
  @media(max-width:768px){
    .header {
      flex-direction: column;
      text-align: center;
    }
    .header-right {
      margin-left: 0;
      margin-top: 20px;
    }
  }
</style>


    <!-- BODY -->
    <div class="main">
      <!-- SIDEBAR -->
      <aside class="sidebar">
        <section>
          <h3><i class="fas fa-address-card"></i> Contact</h3>
          <p><i class="fas fa-phone"></i> 0924854332, 09772518980</p>
          <p><i class="fas fa-envelope"></i> <a href="mailto:minwinmoe123@gmail.com">minwinmoe123@gmail.com</a></p>
          <p><i class="fas fa-map-marker-alt"></i> Chiang Mai, Thailand</p>
        </section>

        <section>
          <h3><i class="fas fa-user"></i> Personal Info</h3>
          <p><strong>Gender:</strong> Male</p>
          <p><strong>DOB:</strong> 15 Oct 1998</p>
          <p><strong>Nationality:</strong> Myanmar (Native - Mon)</p>
          <p><strong>Marital Status:</strong> Single</p>
          <p><strong>Passport:</strong> MJ072280</p>
		<p><strong>Height/Weight:</strong> 172 cm: 57kg</p>
        </section>

        <section>
          <h3><i class="fas fa-language"></i> Languages</h3>
          <ul>
            <li>Mon (Native)</li>
            <li>Burmese (Fluent)</li>
            <li>English (Advanced)</li>
            <li>Thai (Conversational)</li>
          </ul>
        </section>

        <section>
          <h3><i class="fas fa-star"></i> Skills</h3>
          <ul>
            <li>Excellent Communication</li>
		<li>Good at time-managment</li>
		<li>Flexiblity</li>
            <li>Self-Management</li>
            <li>Presentation Skills</li>
            <li>Adaptable & Friendly</li>
            <li>Team Collaboration</li>
		<li>Patient and Understandable </li>
          </ul>
        </section>

        <section>
          <h3><i class="fas fa-award"></i> Certificates</h3>
          <ul>
            <li>English Four Skill (2018)</li>
 		<li> I-Office Computer (2019) </li>
		<li>Google Digital Marketing and E-Commerce (2025)</li>
 		<li>Career Advancement (2024)</li>
		<li>Mastering E-Learning Designs for Modern Educators ((2025)</li>
		<li>Stress Management and Self-Care (2025)</li>
		<li>Localization in Humanitarian Aid (2025)</li>
            <li>Financial Literacy</li>
          </ul>
        </section>
      </aside>

      <!-- MAIN CONTENT -->
      <div class="content">
        <section>
          <h3>Career Objective</h3>
          <p>Motivated and compassionate English educator with over four years of teaching experience, both onsite and online, committed to fostering an inclusive, engaging, and inspiring learning environment. Passionate about empowering students to achieve their full potential through interactive teaching methods, cultural awareness, and personalized guidance. Skilled in curriculum development, classroom management, and innovative instructional strategies that enhance language proficiency, critical thinking, and confidence. Dedicated to lifelong learning and continuous professional growth, with a strong desire to make a positive impact on students’ academic and personal development.</p>
        </section>

        <section>
          <h3>Work Experience</h3>

          <div class="entry">
            <h4>English Teacher</h4>
            <p class="meta">Mon National Primary School, Ye — 2023–2024</p>
            <ul>
              <li>Improved English proficiency in writing, reading, listening, and speaking.</li>
              <li>Used creative and student-centered teaching methods.</li>
            </ul>
          </div>

          <div class="entry">
            <h4>Content Creator</h4>
            <p class="meta">Online Platforms — 2019–2025</p>
            <ul>
              <li>Produced educational English videos for diverse audiences.</li>
              <li>Built supportive online learning communities.</li>
            </ul>
          </div>

          <div class="entry">
            <h4>Online English Tutor</h4>
            <p class="meta">Zoom (Poy English for All Learners) — 2019–2025</p>
            <ul>
              <li>Delivered engaging online lessons with interactive activities.</li>
              <li>Guided learners in pronunciation, writing, and communication.</li>
            </ul>
          </div>
        </section>

        <section>
          <h3>Education</h3>
<div class="entry">
<h4>Payap University (English Communication Arts)
<p class="meta">2nd Year, 2024-2025</p>
</div>
          <div class="entry">
            <h4>Mon National College (Associate Degree in Teaching)</h4>
            <p class="meta">2022–2024</p>
          </div>

          <div class="entry">
            <h4>Hpa-An University (Mathematics)</h4>
            <p class="meta">2nd Year, 2019–2020</p>
          </div>

          <div class="entry">
            <h4>Mon Intensive English Program</h4>
            <p class="meta">2018</p>
          </div>

          <div class="entry">
            <h4>High School / Matriculation Exam</h4>
            <p class="meta">2017–2018</p>
          </div>
        </section>
      </div>
    </div>
  </div>
</body>
</html>
