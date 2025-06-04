<!-- README.md -->

<div align="center">

  <!-- Profile Image -->
  <img src="https://avatars.githubusercontent.com/u/yourgithubid?v=4" alt="Aksheta Saravanan" width="150" style="border-radius: 50%; margin-bottom: 20px;" />

  <!-- Typing animation using SVG + CSS -->
  <h1>
    <svg width="420" height="40" viewBox="0 0 420 40" fill="none" xmlns="http://www.w3.org/2000/svg">
      <text x="0" y="30" font-family="Segoe UI, Tahoma, Geneva, Verdana, sans-serif" font-size="26" fill="#2c3e50">
        Hi! I'm <tspan fill="#0078d7">Aksheta Saravanan</tspan>
      </text>
      <rect id="cursor" x="100" y="10" width="8" height="25" fill="#0078d7" rx="1" ry="1" >
        <animate attributeName="opacity" values="1;0;1" dur="1.2s" repeatCount="indefinite" />
      </rect>
    </svg>
  </h1>

  <!-- Tagline with typing effect -->
  <h3 style="font-family: 'Courier New', Courier, monospace; color: #34495e; margin-top: -10px;">
    <span id="typed-text"></span><span id="typed-cursor">|</span>
  </h3>

  <!-- Current Role -->
  <p style="font-size: 16px; color: #2d3436; margin-top: 15px;">
    🎓 Student at <strong>PSGiTECH</strong> | 💻 Science Subsystem Developer at <strong>PSG TEAM AURORA</strong>
  </p>

  <!-- Social Icons -->
  <p>
    <a href="https://linkedin.com/in/akshetasaravanan" target="_blank" rel="noopener noreferrer">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" alt="LinkedIn" width="40" height="40" style="margin: 0 10px; transition: transform 0.3s;" />
    </a>
    <a href="https://www.hackerrank.com/akshetasaravanan" target="_blank" rel="noopener noreferrer">
      <img src="https://upload.wikimedia.org/wikipedia/commons/6/65/HackerRank_logo.png" alt="HackerRank" width="40" height="40" style="margin: 0 10px; transition: transform 0.3s;" />
    </a>
    <a href="https://www.leetcode.com/akshetasaravanan" target="_blank" rel="noopener noreferrer">
      <img src="https://leetcode.com/static/images/LeetCode_Logo.png" alt="LeetCode" width="40" height="40" style="margin: 0 10px; transition: transform 0.3s;" />
    </a>
    <a href="https://auth.geeksforgeeks.org/user/akshetasaravanan" target="_blank" rel="noopener noreferrer">
      <img src="https://cdn.worldvectorlogo.com/logos/geeksforgeeks-1.svg" alt="GeeksforGeeks" width="40" height="40" style="margin: 0 10px; transition: transform 0.3s;" />
    </a>
  </p>

  <!-- Tech Stack -->
  <h3 style="color: #2c3e50; margin-top: 30px;">Languages and Tools:</h3>
  <p>
    <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="Arduino" width="40" height="40" style="margin: 8px;" />
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C" width="40" height="40" style="margin: 8px;" />
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="C++" width="40" height="40" style="margin: 8px;" />
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3" width="40" height="40" style="margin: 8px;" />
    <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="Figma" width="40" height="40" style="margin: 8px;" />
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5" width="40" height="40" style="margin: 8px;" />
    <img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" alt="MATLAB" width="40" height="40" style="margin: 8px;" />
    <img src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" alt="OpenCV" width="40" height="40" style="margin: 8px;" />
    <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="Pandas" width="40" height="40" style="margin: 8px;" />
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40" style="margin: 8px;" />
    <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="PyTorch" width="40" height="40" style="margin: 8px;" />
    <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="Scikit-learn" width="40" height="40" style="margin: 8px;" />
    <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="Seaborn" width="40" height="40" style="margin: 8px;" />
    <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="TensorFlow" width="40" height="40" style="margin: 8px;" />
  </p>

</div>

<!-- Typing animation script -->
<script>
  const text = "A little logic, a dash of madness, and a passion for making tech come alive";
  let index = 0;
  const speed = 70;

  function typeWriter() {
    if (index < text.length) {
      document.getElementById("typed-text").innerHTML += text.charAt(index);
      index++;
      setTimeout(typeWriter, speed);
    }
  }

  window.onload = () => {
    typeWriter();
  };
</script>

<style>
  a img:hover {
    transform: scale(1.2);
    filter: drop-shadow(0 0 6px #0078d7);
  }
</style>
