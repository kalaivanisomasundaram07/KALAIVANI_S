<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>About Me</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: 'Poppins', sans-serif;
    }

    body{
      background: linear-gradient(135deg,#0f172a,#111827,#1e293b);
      color:white;
      min-height:100vh;
      padding:40px;
    }

    .container{
      max-width:1200px;
      margin:auto;
    }

    .hero{
      text-align:center;
      padding:60px 20px;
    }

    .hero h1{
      font-size:4rem;
      background: linear-gradient(to right,#38bdf8,#818cf8,#c084fc);
      -webkit-background-clip:text;
      color:transparent;
      margin-bottom:20px;
    }

    .hero p{
      color:#cbd5e1;
      font-size:1.2rem;
      max-width:700px;
      margin:auto;
      line-height:1.8;
    }

    .grid{
      display:grid;
      grid-template-columns: repeat(auto-fit,minmax(300px,1fr));
      gap:25px;
      margin-top:50px;
    }

    .card{
      background: rgba(255,255,255,0.05);
      backdrop-filter: blur(10px);
      border:1px solid rgba(255,255,255,0.1);
      padding:30px;
      border-radius:20px;
      transition:0.4s ease;
      box-shadow:0 8px 20px rgba(0,0,0,0.3);
    }

    .card:hover{
      transform:translateY(-10px);
      border-color:#38bdf8;
    }

    .card h2{
      color:#38bdf8;
      margin-bottom:20px;
      font-size:1.5rem;
    }

    ul{
      list-style:none;
    }

    ul li{
      margin-bottom:12px;
      color:#e2e8f0;
      position:relative;
      padding-left:20px;
    }

    ul li::before{
      content:"✨";
      position:absolute;
      left:0;
    }

    .skills{
      display:flex;
      flex-wrap:wrap;
      gap:12px;
    }

    .skill{
      background:#1e293b;
      padding:10px 18px;
      border-radius:30px;
      border:1px solid #334155;
      transition:0.3s;
    }

    .skill:hover{
      background:#38bdf8;
      color:black;
      transform:scale(1.05);
    }

    .footer{
      margin-top:60px;
      text-align:center;
      color:#94a3b8;
      font-size:0.95rem;
    }

    .highlight{
      color:#38bdf8;
      font-weight:bold;
    }

    @media(max-width:768px){
      .hero h1{
        font-size:2.8rem;
      }
    }
  </style>
</head>

<body>

  <div class="container">

    <section class="hero">
      <h1>Hi, I'm Kalaivani 👋</h1>

      <p>
        Aspiring <span class="highlight">Data Analyst</span> &
        <span class="highlight">Python Developer</span> passionate about
        solving problems, building backend systems, and learning modern
        technologies. Currently mastering Python, SQL, Power BI, Tableau,
        Django, and Data Structures & Algorithms.
      </p>
    </section>

    <section class="grid">

      <div class="card">
        <h2>🚀 About Me</h2>
        <ul>
          <li>Passionate Python Developer</li>
          <li>Aspiring Data Analyst by 2026</li>
          <li>Love solving LeetCode problems</li>
          <li>Interested in APIs & Backend Development</li>
          <li>Always learning new technologies</li>
        </ul>
      </div>

      <div class="card">
        <h2>💻 Tech Stack</h2>

        <div class="skills">
          <div class="skill">Python</div>
          <div class="skill">SQL</div>
          <div class="skill">Django</div>
          <div class="skill">Pandas</div>
          <div class="skill">Power BI</div>
          <div class="skill">Tableau</div>
          <div class="skill">Git</div>
          <div class="skill">HTML</div>
          <div class="skill">CSS</div>
          <div class="skill">JavaScript</div>
        </div>
      </div>

      <div class="card">
        <h2>🏆 Achievements</h2>
        <ul>
          <li>Solved coding challenges on LeetCode</li>
          <li>Built Django dashboard projects</li>
          <li>Learning complete Data Analytics roadmap</li>
          <li>Practicing DSA consistently</li>
        </ul>
      </div>

      <div class="card">
        <h2>📚 Currently Learning</h2>
        <ul>
          <li>Advanced Python</li>
          <li>SQL Optimization</li>
          <li>REST API Development</li>
          <li>Power BI Dashboards</li>
          <li>Data Visualization</li>
        </ul>
      </div>

    </section>

    <div class="footer">
      ⭐ Keep Learning • Keep Building • Keep Growing ⭐
    </div>

  </div>

</body>
</html>
