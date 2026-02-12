# Hi there 👋 It's  me Nathesh
 <p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=24&pause=1000&color=00F7FF&center=true&vCenter=true&width=500&lines=Web+Developer;HTML+%7C+CSS+%7C+JS+%7C+PYTHON+%7c+MYSQL;Love+to+Build+Modern+Web+Application" alt="Typing SVG" />
 </p>
<p>

 <!-- Continuous Typing Effect Demo -->
<div align="center">
  <h2 class="typing" id="typing"></h2>
</div>

<style>
  .typing {
    font-family: monospace;
    border-right: 2px solid #0f0; /* cursor */
    white-space: nowrap;
    overflow: hidden;
    color: #0f0;
  }
</style>

<script>
  const phrases = [
    "🚀 Fast Backend Processing",
    "🎨 Animated UI & Mascot-driven Design",
    "🌗 Dark/Light Theme Toggle",
    "🎧 Multi-Audio & Subtitle Support"
  ];

  let i = 0; // phrase index
  let j = 0; // character index
  let currentPhrase = [];
  let isDeleting = false;
  const speed = 100; // typing speed
  const eraseSpeed = 50; // erasing speed
  const delay = 1000; // pause before erasing

  function loop() {
    const textElement = document.getElementById("typing");

    if (!isDeleting && j < phrases[i].length) {
      currentPhrase.push(phrases[i][j]);
      j++;
      textElement.textContent = currentPhrase.join("");
      setTimeout(loop, speed);
    } else if (isDeleting && j > 0) {
      currentPhrase.pop();
      j--;
      textElement.textContent = currentPhrase.join("");
      setTimeout(loop, eraseSpeed);
    } else if (!isDeleting && j === phrases[i].length) {
      isDeleting = true;
      setTimeout(loop, delay);
    } else if (isDeleting && j === 0) {
      isDeleting = false;
      i = (i + 1) % phrases.length;
      setTimeout(loop, speed);
    }
  }

  loop();
</script>

</p>
 

  
       
  
 
                                                              I'm  computer science and engineering  final year <br><br>
<p>I build engaging web applications by combining thoughtful design with modern web technologies, focusing on responsive layouts and interactive user experiences.</p>
  <img align="right" hight="290" width="370" src="https://www.tech-bhai.com/wp-content/uploads/2024/10/gifImg-8.gif" alt="no gif load"><br>

My profile:
- 🔭 Here's my [portfolio](https://nathesh-portfolio.vercel.app/) <br><br>
- 🔭 Here's my [Linkedin](https://www.linkedin.com/in/nathesh1305)<br>

<br><br><br><br><hr>

### 🚀 Tech Stack    
<div align="left">
  <img src="https://skillicons.dev/icons?i=html,css,js,mysql,python,flask,java,github&theme=light" />
</div><hr>

### 🚀 IDE and Tools I Use
<div>
<img src="https://skillicons.dev/icons?i=pycharm,vscode,ae" />
 <img src="https://img.icons8.com/fluency/48/microsoft-365.png" alt="microsoft-365"/>
 <img  src="https://img.icons8.com/color/48/virtualbox.png" alt="virtualbox"/>
 <img  src="https://img.icons8.com/color/48/computer-support.png" alt="computer-support"/>
 </div>

---
### 💻 Workspace spec
![LeetCode Stats](https://leetcard.jacoblin.cool/NATHESH?theme=dark&font=Marmelad&ext=contest)
### 📈 Contribution Graph
[![Ashutosh's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=NATHESH6&bg_color=24292f&color=f5f5f5&line=7ef7f5&point=07eded&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)
