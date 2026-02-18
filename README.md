

<svg width="1100" height="350" viewBox="0 0 1100 350" xmlns="http://www.w3.org/2000/svg">

  <defs>
    <!-- Background Gradient -->
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#000000"/>
      <stop offset="100%" stop-color="#0f2027"/>
    </linearGradient>

    <!-- Glow Effect -->
    <filter id="neonGlow">
      <feGaussianBlur stdDeviation="3.5" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <style>
      .title {
        fill: #00ff41;
        font-size: 42px;
        font-family: monospace;
        font-weight: bold;
        filter: url(#neonGlow);
      }

      .subtitle {
        fill: #00ffaa;
        font-size: 18px;
        font-family: monospace;
      }

      .info {
        fill: #ffffff;
        font-size: 15px;
        font-family: monospace;
      }

      .matrix {
        fill: #00ff41;
        font-size: 14px;
        font-family: monospace;
        opacity: 0.15;
      }

      .tech {
        font-size: 18px;
        font-family: monospace;
        font-weight: bold;
      }

      .rotate {
        transform-origin: center;
        animation: spin 12s linear infinite;
      }

      @keyframes spin {
        from { transform: rotate(0deg); }
        to { transform: rotate(360deg); }
      }

      .float {
        animation: float 4s ease-in-out infinite;
      }

      @keyframes float {
        0% { transform: translateY(0px); }
        50% { transform: translateY(-10px); }
        100% { transform: translateY(0px); }
      }

      .codeMove {
        animation: codeScroll 6s linear infinite;
      }

      @keyframes codeScroll {
        from { transform: translateY(0px); }
        to { transform: translateY(-40px); }
      }
    </style>
  </defs>

  <!-- Background -->
  <rect width="100%" height="100%" fill="url(#bg)" />

  <!-- Matrix Rain Effect -->
  <text x="50" y="40" class="matrix">101010010110101010101010101010101010101</text>
  <text x="300" y="100" class="matrix">11010101010100101010101011010101010101</text>
  <text x="600" y="70" class="matrix">10101010101101010101010101010101010101</text>
  <text x="900" y="130" class="matrix">01010101010101011010101010101010101010</text>

  <!-- Personal Info -->
  <text x="60" y="100" class="title">NATHESH PV</text>
  <text x="60" y="140" class="subtitle">Hacker Mode | Full Stack Developer</text>

  <text x="60" y="180" class="info">📍 Thevur, Salem</text>
  <text x="60" y="205" class="info">📧 swffsfwf@gmail.com</text>
  <text x="60" y="230" class="info">📱 9822978989</text>

  <!-- Rotating Tech Stack Circle -->
  <g class="rotate" transform="translate(850,170)">
    <text x="-60" y="-70" fill="#f89820" class="tech">Java</text>
    <text x="60" y="-50" fill="#3776AB" class="tech">Python</text>
    <text x="70" y="40" fill="#F7DF1E" class="tech">JS</text>
    <text x="-40" y="80" fill="#E34F26" class="tech">HTML5</text>
    <text x="-110" y="40" fill="#1572B6" class="tech">CSS3</text>
    <text x="-90" y="-40" fill="#00758F" class="tech">MySQL</text>
    <text x="0" y="0" fill="#ffffff" class="tech">GitHub</text>
  </g>

  <!-- Computer Setup -->
  <g class="float">
    <!-- Monitor -->
    <rect x="500" y="100" width="250" height="150" rx="10" fill="#111"/>
    <rect x="520" y="120" width="210" height="110" fill="#001f00" />

    <!-- Moving Code -->
    <g class="codeMove">
      <text x="530" y="150" fill="#00ff41" font-family="monospace" font-size="12">
        &lt;html&gt;
      </text>
      <text x="530" y="165" fill="#00ff41" font-family="monospace" font-size="12">
        console.log("Hacked");
      </text>
      <text x="530" y="180" fill="#00ff41" font-family="monospace" font-size="12">
        SELECT * FROM users;
      </text>
      <text x="530" y="195" fill="#00ff41" font-family="monospace" font-size="12">
        System.out.println("Hi");
      </text>
    </g>

    <!-- Stand -->
    <rect x="600" y="250" width="50" height="15" fill="#555"/>

    <!-- Keyboard -->
    <rect x="470" y="280" width="310" height="15" rx="5" fill="#222"/>

    <!-- Mouse -->
    <ellipse cx="820" cy="287" rx="12" ry="8" fill="#333"/>

    <!-- Coffee -->
    <rect x="430" y="260" width="20" height="25" fill="#444"/>
    <ellipse cx="440" cy="260" rx="10" ry="5" fill="#666"/>
  </g>

</svg>


# Hi there 👋 It's  me Nathesh
 <p align="center">
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1000&width=700&color=00F7FF&center=true&vCenter=true&lines=Hello%2CI'm+Nathesh!;Welcome+to+my+profile;I'm+a+web+developer+%26+web+designer;I+love+coding+and+creating;Like+Html%7C+CSS%7C+JS+%7CMYSQL+%26+Python;Love+to+build+modern+and+responsive+websites;Feel+free+to+explore+my+work!" alt="Typing SVG" /></a>
 </p>
 <h2>💫About Me:</h2> 
 
🔭 I am a final-year Computer Science and Engineering student at CIET College with a strong passion for Web Development and Machine Learning Engineering. <br><br>
👯I enjoy building intelligent systems that solve real-world problems using data-driven approaches.<br><br>
🤝During my third year, I successfully completed a project titled “Develop an AI System to Identify and Block Phishing Emails”, where I built a phishing email detection system using Machine Learning and XG-Boost.<br><br>  <img align="right" hight="290" width="370" src="https://www.tech-bhai.com/wp-content/uploads/2024/10/gifImg-8.gif" alt="no gif load"><br>
🌱 The project was developed using Python, Flask, HTML, and CSS, focusing on building a practical and user-friendly web-based solution.<br><br>
💬 I'm Currently, my final-year project focuses on "Cyber Hacking Breach Prediction and Detection" using Machine Learning and XG-Boost, where I'm working on developing a predictive system to identify potential cyber threats and security breaches.<br><br>
⚡ Both project my role is leading &  support my teams members , Frontend designing and backend development using ML ,Flask in Python<br> 



## 🌐 Socials:
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/natheshvenkateswaran3) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/nathesh1305) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:megaladevi2084@gmail.com) 
<a href="https://nathesh-portfolio.vercel.app/"><img width="40" height="20" src="https://img.icons8.com/3d-fluency/94/briefcase--v1.png" alt="portfolio"/></a>
<br><hr>

### 🚀 Tech Stack    
<div align="left">
  <img src="https://skillicons.dev/icons?i=html,css,js,mysql,python,flask,java&theme=light" />
</div><hr>

### 🚀 IDE and Tools I Use
<div>
<img src="https://skillicons.dev/icons?i=pycharm,vscode,ae" />
 <img src="https://img.icons8.com/fluency/48/microsoft-365.png" alt="microsoft-365"/>
 <img  src="https://img.icons8.com/color/48/virtualbox.png" alt="virtualbox"/>
 <img  src="https://img.icons8.com/color/48/computer-support.png" alt="computer-support"/>
 <img width="50" height="50" src="https://img.icons8.com/fluency/48/audacity.png" alt="audacity"/>
  <img src="https://skillicons.dev/icons?i=github&theme=light" />
 </div>

---
### 💻 Workspace spec
![LeetCode Stats](https://leetcard.jacoblin.cool/NATHESH?theme=dark&font=Marmelad&ext=contest)

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

### 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=NATHESH6&theme=dark&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=NATHESH6&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=NATHESH6&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)


### 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=NATHESH6&theme=radical&no-frame=false&no-bg=true&margin-w=4)

### 🔝 Top Contributed Repo
![](https://github-contributor-stats.vercel.app/api?username=NATHESH6&limit=6&theme=dark&combine_all_yearly_contributions=true)


### 📈 Contribution Graph
[![NATHESH6's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=NATHESH6&bg_color=24292f&color=f5f5f5&line=7ef7f5&point=07eded&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)
