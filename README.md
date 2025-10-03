<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Skills Dashboard</title>
<style>
  body {
    font-family: Arial, sans-serif;
    background: #f4f6f8;
    padding: 20px;
  }
  h2 {
    text-align: center;
    color: #333;
  }
  .skills-container {
    max-width: 800px;
    margin: auto;
  }
  .skill {
    margin: 20px 0;
  }
  .skill-name {
    font-weight: bold;
    margin-bottom: 5px;
  }
  .skill-bar {
    background: #ddd;
    border-radius: 20px;
    overflow: hidden;
    height: 25px;
  }
  .skill-level {
    height: 100%;
    text-align: right;
    padding-right: 10px;
    color: white;
    line-height: 25px;
    font-weight: bold;
    border-radius: 20px;
  }
  .angular { width: 80%; background: #DD0031; }
  .typescript { width: 75%; background: #007ACC; }
  .html5 { width: 95%; background: #E34F26; }
  .css3 { width: 85%; background: #1572B6; }
  .nodejs { width: 85%; background: #339933; }
  .express { width: 80%; background: #000000; }
  .mongodb { width: 70%; background: #4EA94B; }
  .git { width: 90%; background: #F05032; }
  .docker { width: 60%; background: #2496ED; }
  .vscode { width: 95%; background: #0078d7; }
</style>
</head>
<body>

<h2>📊 Skills Dashboard</h2>
<div class="skills-container">

  <div class="skill">
    <div class="skill-name">Angular 🔴</div>
    <div class="skill-bar"><div class="skill-level angular">80%</div></div>
  </div>

  <div class="skill">
    <div class="skill-name">TypeScript 💙</div>
    <div class="skill-bar"><div class="skill-level typescript">75%</div></div>
  </div>

  <div class="skill">
    <div class="skill-name">HTML5 🖌️</div>
    <div class="skill-bar"><div class="skill-level html5">95%</div></div>
  </div>

  <div class="skill">
    <div class="skill-name">CSS3 🎨</div>
    <div class="skill-bar"><div class="skill-level css3">85%</div></div>
  </div>

  <div class="skill">
    <div class="skill-name">Node.js 🟢</div>
    <div class="skill-bar"><div class="skill-level nodejs">85%</div></div>
  </div>

  <div class="skill">
    <div class="skill-name">Express.js ⚙️</div>
    <div class="skill-bar"><div class="skill-level express">80%</div></div>
  </div>

  <div class="skill">
    <div class="skill-name">MongoDB 🍃</div>
    <div class="skill-bar"><div class="skill-level mongodb">70%</div></div>
  </div>

  <div class="skill">
    <div class="skill-name">Git 🛠️</div>
    <div class="skill-bar"><div class="skill-level git">90%</div></div>
  </div>

  <div class="skill">
    <div class="skill-name">Docker 🐳</div>
    <div class="skill-bar"><div class="skill-level docker">60%</div></div>
  </div>

  <div class="skill">
    <div class="skill-name">VS Code 💻</div>
    <div class="skill-bar"><div class="skill-level vscode">95%</div></div>
  </div>

</div>

</body>
</html>
