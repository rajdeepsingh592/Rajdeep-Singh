![logo](https://github.com/rajdeepsingh592/Rajdeep-Singh/blob/main/1.png)<h1 align="center">Hi 👋, I'm Rajdeep Singh</h1>
<h3 align="center">A passionate AIML student from MIT, specializing in AIML</h3>

<!-- GIF Banner -->
<p align="center">
  <img src="https://developers.giphy.com/branch/master/static/api-c99e353f761d318322c853c03ebcf21b.gif" alt="GIF Banner" width="100%" height="250"/>
</p>



<p align="left">
  <img src="https://komarev.com/ghpvc/?username=rajdeepsingh&label=Profile%20views&color=blue&style=plastic" alt="rajdeepsingh" />
</p>

<h2 align="left">🌟 About Me:</h2>
<ul>
  <li>🚀 I'm currently working on IoT, electronics, and AI-based projects.</li>
  <li>💡 Exploring new technologies and constantly trying to innovate in the fields of robotics and AI.</li>
  <li>🎓 4th Year AIML student looking for new opportunities to apply my knowledge in real-world applications.</li>
</ul>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>Rajdeep Singh – Neon Profile Section</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />

  <!--  =====  FONTS  =====  -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;700&display=swap" rel="stylesheet" />

  <style>
    /* ===== RESET & CORE ===== */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      min-height: 100vh;
      font-family: "Poppins", sans-serif;
      color: #fff;
      background: #000;
      overflow-x: hidden;
    }

    /* =====  ANIMATED NEON–SMOKE BACKGROUND  ===== */
    body::before {
      content: "";
      position: fixed;
      inset: 0;
      background: linear-gradient(
        60deg,
        #ff0080,
        #ff8c00,
        #40e0d0,
        #8a2be2,
        #ff0080
      );
      background-size: 500% 500%;
      filter: blur(120px);
      animation: bgmove 15s ease infinite;
      z-index: -2;
    }

    @keyframes bgmove {
      0% {
        background-position: 0% 50%;
      }
      50% {
        background-position: 100% 50%;
      }
      100% {
        background-position: 0% 50%;
      }
    }

    /* Optional subtle smoke overlay (can be removed if too heavy) */
    body::after {
      content: "";
      position: fixed;
      inset: 0;
      background: url("https://raw.githubusercontent.com/rajdeepsingh592/Rajdeep-Singh/main/smoke.png") repeat;
      opacity: 0.05;
      animation: smoke 40s linear infinite;
      z-index: -1;
    }

    @keyframes smoke {
      0% {
        transform: translateY(0);
      }
      100% {
        transform: translateY(-100%);
      }
    }

    /* =====  SECTIONS  ===== */
    section {
      padding: 40px 5%;
    }

    h2 {
      margin-bottom: 24px;
      color: #0ff;
      text-shadow: 0 0 10px #0ff, 0 0 25px #0ff;
      font-size: 1.75rem;
    }

    /* =====  LOGO GRID  ===== */
    .logo-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 28px;
    }

    .logo-card {
      width: 80px;
      height: 80px;
      padding: 10px;
      border-radius: 18px;
      background: rgba(255, 255, 255, 0.05);
      box-shadow: 0 10px 22px rgba(0, 0, 0, 0.6), 0 0 15px rgba(0, 255, 255, 0.6);
      perspective: 800px; /* enables 3‑D */
      transition: transform 0.7s ease;
      transform-style: preserve-3d;
    }

    /* flip card on hover */
    .logo-card:hover {
      transform: rotateY(180deg);
    }

    /* logo icons */
    .logo-card img {
      width: 100%;
      height: 100%;
      object-fit: contain;
      backface-visibility: hidden; /* hide backside during flip */
    }

    /* =====  GitHub stats (kept centered)  ===== */
    .stats {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 24px;
    }

    .stats img {
      max-width: 100%;
    }

    /*  ----  LINKS  ---- */
    a {
      text-decoration: none;
      color: inherit;
    }
  </style>
</head>
<body>
  <!--  =========  CONNECT  ========= -->
  <section>
    <h2>🔗 Connect with me</h2>
    <div class="logo-grid">
      <!--  LeetCode  -->
      <a href="https://www.leetcode.com/rajdeepsingh5272" target="_blank" rel="noreferrer">
        <div class="logo-card">
          <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="LeetCode" />
        </div>
      </a>
      <!--  Add more social icons here in the same pattern if desired  -->
    </div>
  </section>

  <!--  =========  LANGUAGES & TOOLS  ========= -->
  <section>
    <h2>🛠 Languages and Tools</h2>
    <div class="logo-grid">
      <a href="https://developer.android.com" target="_blank" rel="noreferrer">
        <div class="logo-card">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="Android" />
        </div>
      </a>
      <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer">
        <div class="logo-card">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3" />
        </div>
      </a>
      <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer">
        <div class="logo-card">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5" />
        </div>
      </a>
      <a href="https://www.java.com" target="_blank" rel="noreferrer">
        <div class="logo-card">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" />
        </div>
      </a>
      <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer">
        <div class="logo-card">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" />
        </div>
      </a>
      <a href="https://www.mysql.com/" target="_blank" rel="noreferrer">
        <div class="logo-card">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" />
        </div>
      </a>
      <a href="https://opencv.org/" target="_blank" rel="noreferrer">
        <div class="logo-card">
          <img src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" alt="OpenCV" />
        </div>
      </a>
      <a href="https://www.python.org" target="_blank" rel="noreferrer">
        <div class="logo-card">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" />
        </div>
      </a>
      <a href="https://www.selenium.dev" target="_blank" rel="noreferrer">
        <div class="logo-card">
          <img src="https://raw.githubusercontent.com/detain/svg-logos/780f25886640cef088af994181646db2f6b1a3f8/svg/selenium-logo.svg" alt="Selenium" />
        </div>
      </a>
      <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer">
        <div class="logo-card">
          <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="TensorFlow" />
        </div>
      </a>
    </div>
  </section>

  <!--  =========  GITHUB STATS  ========= -->
  <section>
    <h2>📊 GitHub Stats</h2>
    <div class="stats">
      <img
        src="https://github-readme-stats.vercel.app/api?username=rajdeepsingh&show_icons=true&theme=tokyonight&locale=en"
        alt="Rajdeep GitHub stats"
      />
      <img
        src="https://github-readme-streak-stats.herokuapp.com/?user=rajdeepsingh&theme=tokyonight"
        alt="Rajdeep GitHub streak"
      />
    </div>
  </section>
</body>
</html>

