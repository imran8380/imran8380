<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Abdullah Al Imran | Research Portfolio</title>
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
<style>
/* Basic Reset and Fonts */
*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif;}
body{background:#0d0d0d;color:white;overflow-x:hidden;}

/* Navbar */
nav{width:100%;padding:25px 60px;display:flex;justify-content:space-between;align-items:center;background:#111;position:fixed;top:0;z-index:1000;transition:0.3s;}
nav.scrolled{box-shadow:0 4px 12px rgba(0,0,0,0.5);}
nav .logo{font-size:1.8rem;font-weight:700;}
nav .logo span{color:#ff0059;}
nav ul{display:flex;gap:40px;list-style:none;}
nav ul li a{text-decoration:none;color:white;font-size:1.1rem;font-weight:500;transition:0.3s;}
nav ul li a:hover{color:#ff0059;}

/* Hero Section */
.hero{width:100%;min-height:100vh;display:flex;flex-direction:column;justify-content:center;align-items:flex-start;padding:0 60px;background:linear-gradient(135deg,#111,#0d0d0d);}
.hero h1{font-size:4rem;font-weight:700;margin-top:50px;color:white;}
.hero h1 span{color:#ff0059;}
.hero h2{font-size:3.3rem;font-weight:700;margin:20px 0;color:#fff;}
.btns{display:flex;gap:20px;margin-top:40px;}
.btn{display:inline-block;padding:14px 26px;border-radius:14px;font-weight:600;cursor:pointer;transition:0.25s ease;color:#fff;border:none;background:linear-gradient(135deg,#ff1e57,#ff5f8e);box-shadow:0 4px 12px rgba(255,30,87,0.35);}
.btn:hover{transform:translateY(-5px) scale(1.03);box-shadow:0 8px 20px rgba(255,30,87,0.55);}
.btn.ghost{background:transparent;border:2px solid #ff1e57;color:#ff1e57;box-shadow:none;}
.btn.ghost:hover{background:rgba(255,30,87,0.15);color:#fff;transform:translateY(-4px);box-shadow:0 6px 14px rgba(255,30,87,0.4);}

/* About Section */
.about{width:100%;padding:120px 60px;display:flex;gap:60px;align-items:center;flex-wrap:wrap;}
.about .text-box{max-width:850px;}
.about h2{font-size:3rem;margin-bottom:20px;color:#ff0059;}
.about p{font-size:1.1rem;line-height:1.7;margin-bottom:30px;}
.tab-buttons{display:flex;gap:15px;margin-bottom:20px;}
.tab-buttons button{padding:10px 20px;border:none;border-radius:12px;background:#222;color:white;cursor:pointer;transition:0.3s;}
.tab-buttons button.active{background:#ff0059;color:white;}
.tab-content{display:none;}
.tab-content.active{display:block;}
.skill-bar{height:20px;width:0;background:#ff0059;border-radius:12px;margin-bottom:12px;transition:1s;}
.skill-name{margin-bottom:5px;font-weight:600;}

/* Projects Section */
.projects-section{padding:80px 60px;}
.projects-section h2{font-size:2.8rem;margin-bottom:30px;color:#ff0059;}
.proj-card{border:1px solid #333;padding:30px;border-radius:20px;margin-bottom:25px;transition:0.3s;}
.proj-card:hover{transform:translateY(-8px);box-shadow:0 10px 25px rgba(255,30,87,0.5);}
.proj-links{margin-top:15px; display:flex; gap:10px;}
.proj-links a{padding:10px 16px;border-radius:12px;font-weight:600;background:linear-gradient(135deg,#ff1e57,#ff5f8e);color:#fff;text-decoration:none;transition:0.25s;}
.proj-links a:hover{transform:translateY(-4px);box-shadow:0 6px 18px rgba(255,30,87,0.5);}

/* Contact Section - Reordered for professional left-to-right flow: Form then Contact Info */
.contact-section{padding:100px 60px;display:flex;flex-wrap:wrap;justify-content:center;gap:50px;}
.contact-card,.message-card{background:#1a1a1a;padding:40px;border-radius:20px;flex:1 1 350px;max-width:400px;box-shadow:0 6px 18px rgba(0,0,0,0.4);}
.contact-card h3,.message-card h3{color:#ff0059;margin-bottom:25px;text-align:center;font-size:1.8rem;}
.contact-card p{margin-bottom:15px;}
.contact-card a{color:#ff0059;text-decoration:none;}
.contact-card a:hover{text-decoration:underline;}
.contact-icons{text-align:center;margin-top:20px;}
.contact-icons a{margin:0 12px;color:white;font-size:1.6em;transition:0.3s;}
.contact-icons a:hover{color:#ff0059;}
.message-card input,.message-card textarea{width:100%;padding:12px;margin-bottom:15px;border-radius:8px;border:none;background:#333;color:white;}
.message-card input:focus,.message-card textarea:focus{outline:none;border:2px solid #ff0059;}
.message-card button{background:linear-gradient(135deg,#ff1e57,#ff5f8e);color:white;padding:12px 20px;border:none;border-radius:8px;cursor:pointer;transition:0.3s;width:100%;font-weight:600;font-size:1.1em;}
.message-card button:hover{background:#ff4d4d;}

/* Responsive */
@media(max-width:900px){
  .hero{align-items:center;text-align:center;}
  .about{flex-direction:column;text-align:center;}
}
</style>
</head>
<body>

<nav id="navbar">
  <div class="logo">Abdullah<span>| CSE Student</span></div>
  <ul>
    <li><a href="#hero">Home</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<section class="hero" id="hero">
  <h1>Hi, I am <span>Abdullah Al Imran</span></h1>
  <h2>CSE Student | Programmer</h2>
  <div class="btns">
    <a href="#" class="btn">Download CV</a>
    <a href="https://github.com/imran8380" target="_blank" class="btn ghost">Visit GitHub</a>
  </div>
</section>

<section class="about" id="about">
  <div class="text-box">
    <h2>About Me</h2>
    <p>About a jeta ache oitai</p>

    <div class="tab-buttons">
      <button class="active" data-tab="skills">Skills</button>
      <button data-tab="education">Education</button>
    </div>

    <div class="tab-content active" id="skills">
      <div class="skill-name">C, C++</div>
      <div class="skill-bar" style="width:92%"></div>
      <div class="skill-name">Java</div>
      <div class="skill-bar" style="width:85%"></div>
      <div class="skill-name">Adobe Photoshop, Adobe Lightroom, CapCut</div>
      <div class="skill-bar" style="width:78%"></div>
      <div class="skill-name">Microsoft Office (Word, Excel, PowerPoint)</div>
      <div class="skill-bar" style="width:88%"></div>
    </div>

  <div class="tab-content" id="education">

  <div class="education-wrapper">

    <div class="edu-card">
      <h3>B.Sc. in Computer Science & Engineering (Running)</h3>
      <span class="edu-year">Bangladesh University of Business and Technology (BUBT)</span>
      <p>Currently pursuing CSE with focus on algorithms, software development and research.</p>
    </div>

    <div class="edu-card">
      <h3>Higher Secondary Certificate (HSC)</h3>
      <span class="edu-year">Govt. Gopalganj College, Gopalganj</span>
    </div>

  </div>

</div>

</div>



</section>
<section class="projects-section" id="projects">
  <h2>Projects & Research Work 🔬</h2>
  <div class="proj-card">
    <h3>SDP 101: DNA & RNA Sequence Analyzer</h3>
    <p>A sequence analysis tool for DNA and RNA — includes GC-content calculator, ORF finder, and basic sequence statistics. Implemented using C/C++ with emphasis on correctness and performance.</p>
    <div class="proj-links">
      <a href="#" aria-label="Live Demo (Placeholder)">Live Demo</a>
      <a href="https://github.com/imran8380/SDP-101" target="_blank" aria-label="SDP-101 GitHub Repository">GitHub</a>
    </div>
  </div>
  <div class="proj-card">
    <h3>EEE: Superposition Theorem (Lab)</h3>
    <p>Experiment and report on Superposition Theorem demonstrating circuit analysis techniques and measurement of voltage/current contributions from independent sources.</p>
    <div class="proj-links">
      <a href="#" aria-label="Lab Report (Placeholder)">Report</a>
      <a href="#" target="_blank" aria-label="GitHub Repository (Placeholder)">GitHub</a>
    </div>
  </div>

</section>

<section class="contact-section" id="contact">
  <div class="message-card">
    <h3>Send a Message ✉️</h3>
    <form action="mailto:imran.stu.8380@gmail.com" method="post" enctype="text/plain">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" rows="6" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </div>
  <div class="contact-card">
    <h3>Connect with Me 🌐</h3>
    <p>Email: <a href="mailto:imran.stu.8380@gmail.com">imran.stu.8380@gmail.com</a></p>
    <p>Phone: <a href="tel:+8801756644097">+880 1756-644097</a></p>
    <p>GitHub: <a href="https://github.com/imran8380" target="_blank">github.com/imran8380</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/imran8380/" target="_blank">linkedin.com/in/imran8380</a></p>
    <p>Facebook: <a href="https://www.facebook.com/shadow.boy.2004" target="_blank">facebook.com/shadow.boy.2004</a></p>
    <div class="contact-icons">
      <a href="https://github.com/imran8380" target="_blank" aria-label="GitHub"><i class="fab fa-github"></i></a>
      <a href="mailto:imran.stu.8380@gmail.com" aria-label="Email"><i class="fas fa-envelope"></i></a>
      <a href="tel:+8801756644097" aria-label="Phone"><i class="fas fa-phone"></i></a>
      <a href="https://www.linkedin.com/in/imran8380/" target="_blank" aria-label="LinkedIn"><i class="fab fa-linkedin"></i></a>
      <a href="https://www.facebook.com/shadow.boy.2004" target="_blank" aria-label="Facebook"><i class="fab fa-facebook"></i></a>
    </div>
  </div>
</section>

<script>
// Tabs functionality
const tabButtons = document.querySelectorAll('.tab-buttons button');
const tabContents = document.querySelectorAll('.tab-content');

tabButtons.forEach(btn=>{
  btn.addEventListener('click',()=>{
    tabButtons.forEach(b=>b.classList.remove('active'));
    btn.classList.add('active');
    const tab = btn.getAttribute('data-tab');
    tabContents.forEach(tc=>tc.classList.remove('active'));
    document.getElementById(tab).classList.add('active');
  });
});

// Navbar scroll shadow
window.addEventListener('scroll',()=>{
  document.getElementById('navbar').classList.toggle('scrolled', window.scrollY>50);
});
</script>

</body>
</html>
