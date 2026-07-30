<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Arshdeep Singh | Cybersecurity Engineer</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:#08131f;
color:#fff;
}

header{
width:100%;
position:fixed;
top:0;
left:0;
background:#091a2c;
padding:20px 8%;
display:flex;
justify-content:space-between;
align-items:center;
z-index:1000;
box-shadow:0 0 10px rgba(0,0,0,.4);
}

header h2{
color:#00d4ff;
}

nav a{
text-decoration:none;
color:white;
margin-left:25px;
transition:.3s;
font-weight:500;
}

nav a:hover{
color:#00d4ff;
}

section{
padding:100px 8%;
}

.hero{
min-height:100vh;
display:flex;
justify-content:space-between;
align-items:center;
gap:50px;
}

.hero-text h1{
font-size:55px;
margin-bottom:10px;
}

.hero-text h2{
font-size:30px;
color:#00d4ff;
margin-bottom:20px;
}

.hero-text p{
line-height:1.8;
font-size:17px;
margin-bottom:25px;
}

.btn{
display:inline-block;
padding:14px 35px;
background:#00d4ff;
color:#08131f;
text-decoration:none;
border-radius:30px;
font-weight:bold;
transition:.3s;
}

.btn:hover{
transform:translateY(-4px);
}

.hero img{
width:350px;
border-radius:50%;
border:5px solid #00d4ff;
box-shadow:0 0 40px #00d4ff55;
}

.title{
text-align:center;
margin-bottom:50px;
font-size:35px;
color:#00d4ff;
}

.about{
line-height:2;
font-size:17px;
text-align:center;
}

.skills{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.skill-box{
background:#0f2236;
padding:25px;
border-radius:15px;
transition:.3s;
}

.skill-box:hover{
transform:translateY(-8px);
}

.skill-box h3{
margin-bottom:15px;
color:#00d4ff;
}

.skill-box ul{
padding-left:20px;
line-height:2;
}

.projects{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(320px,1fr));
gap:30px;
}

.project{
background:#0f2236;
padding:25px;
border-radius:15px;
transition:.3s;
}

.project:hover{
transform:translateY(-10px);
}

.project h3{
color:#00d4ff;
margin-bottom:15px;
}

.project p{
line-height:1.8;
}

.certificates{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.cert{
background:#0f2236;
padding:20px;
border-radius:10px;
text-align:center;
}

.contact{
text-align:center;
}

.contact p{
margin:15px;
font-size:18px;
}

footer{
text-align:center;
padding:30px;
background:#091a2c;
margin-top:50px;
}

@media(max-width:900px){

.hero{
flex-direction:column-reverse;
text-align:center;
}

.hero img{
width:250px;
}

header{
flex-direction:column;
}

nav{
margin-top:15px;
}

}

</style>

</head>
<body>

<header>

<h2>Arshdeep Singh</h2>

<nav>
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#projects">Projects</a>
<a href="#certifications">Certifications</a>
<a href="#contact">Contact</a>
</nav>

</header>

<section class="hero" id="home">

<div class="hero-text">

<h1>Hello, I'm Arshdeep Singh 👋</h1>

<h2>Cybersecurity Engineer | Ethical Hacker | Security Trainer</h2>

<p>

Cybersecurity professional with hands-on experience in Ethical Hacking,
Network Security, Linux Administration, SIEM, AI-powered Cybersecurity,
Web Security, and Security Awareness Training.

Passionate about securing digital infrastructure and educating future
cybersecurity professionals through practical learning.

</p>

<a href="#" class="btn">Download Resume</a>

</div>

<img src="https://images.unsplash.com/photo-1518770660439-4636190af475?w=600" alt="Cyber Security">

</section>

<section id="about">

<h2 class="title">About Me</h2>

<p class="about">

I am a Cybersecurity Engineer with expertise in Ethical Hacking,
Network Security, Linux Administration, SIEM implementation,
and AI-driven Cybersecurity solutions.

I enjoy building practical cybersecurity labs, conducting training
sessions, performing penetration testing, and researching modern
security threats.

</p>

</section>

<section id="skills">

<h2 class="title">Technical Skills</h2>

<div class="skills">

<div class="skill-box">

<h3>Cybersecurity</h3>

<ul>

<li>Ethical Hacking</li>

<li>Penetration Testing</li>

<li>Web Security</li>

<li>VAPT</li>

<li>SIEM (Wazuh)</li>

<li>OWASP Top 10</li>

</ul>

</div>

<div class="skill-box">

<h3>Security Tools</h3>

<ul>

<li>Nmap</li>

<li>Burp Suite</li>

<li>Wireshark</li>

<li>Hydra</li>

<li>Gobuster</li>

<li>Nikto</li>

<li>SQLMap</li>

<li>Metasploit</li>

</ul>

</div>

<div class="skill-box">

<h3>Networking</h3>

<ul>

<li>TCP/IP</li>

<li>OSI Model</li>

<li>DNS</li>

<li>DHCP</li>

<li>VPN</li>

<li>Firewall</li>

<li>pfSense</li>

</ul>

</div>

<div class="skill-box">

<h3>Programming</h3>

<ul>

<li>Java</li>

<li>Python</li>

<li>Bash</li>

<li>JavaScript</li>

<li>HTML</li>

<li>CSS</li>

</ul>

</div>

</div>

</section>

<section id="projects">

<h2 class="title">Projects</h2>

<div class="projects">

<div class="project">

<h3>AI-Powered Cybersecurity Training</h3>

<p>

Developed a structured AI-integrated cybersecurity curriculum including
Ethical Hacking, Linux, Networking, AI Security Automation,
Prompt Engineering, and SOC Analyst training.

</p>

</div>

<div class="project">

<h3>Digital Fraud Response & Monitoring System</h3>

<p>

Implemented Wazuh SIEM for centralized log monitoring, attack detection,
dashboard creation, and incident response.

</p>

</div>

<div class="project">

<h3>Self Hosted WebRTC Infrastructure</h3>

<p>

Built a secure Linux-based WebRTC server using Docker,
TURN/STUN servers, TLS, Reverse Proxy,
and production deployment techniques.

</p>

</div>

<div class="project">

<h3>Network Security Lab</h3>

<p>

Created enterprise-level firewall lab using pfSense,
virtual machines, IDS/IPS concepts,
and advanced networking security configurations.

</p>

</div>

</div>

</section>

<section id="certifications">

<h2 class="title">Certifications</h2>

<div class="certificates">

<div class="cert">

AWS Fundamentals

</div>

<div class="cert">

Cybersecurity Internship

</div>

<div class="cert">

Networking Internship

</div>

<div class="cert">

Ethical Hacking Workshops

</div>

<div class="cert">

Linux Administration

</div>

<div class="cert">

AI Powered Cybersecurity

</div>

</div>

</section>

<section id="contact">

<h2 class="title">Contact Me</h2>

<div class="contact">

<p>📧 sa6763205@gmail.com</p>

<p>💼 LinkedIn: https://www.linkedin.com/in/er-arshdeep-singh-742973240/</p>

<p>🌐 Portfolio: cyber-persona.onrender.com</p>

<p>💻 GitHub: github.com/arshdeepsingh157</p>

</div>

</section>

<footer>

© 2026 Arshdeep Singh | Cybersecurity Engineer

</footer>

</body>
</html>
