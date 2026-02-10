<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Dharshini S | Premium Portfolio</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet" />
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />
<style>
:root{
  --primary:#69d2e7;
  --bg:#0b0d14;
  --card:#151826;
  --text:#f5f7ff;
  --muted:#9aa0b3;
}
body.light{
  --bg:#f4f6fb;
  --card:#ffffff;
  --text:#0f1220;
  --muted:#555;
}
*{box-sizing:border-box}
body{
  margin:0;font-family:'Poppins',sans-serif;
  background:radial-gradient(circle at top,#101426,var(--bg));
  color:var(--text);scroll-behavior:smooth
}
a{text-decoration:none;color:inherit}
.container{max-width:1150px;margin:auto;padding:0 1rem}

#progress{position:fixed;top:0;left:0;height:3px;width:0;background:linear-gradient(90deg,var(--primary),#4fbcd3);z-index:2000}

header{position:fixed;width:100%;top:0;z-index:1000;background:rgba(11,13,20,.85);backdrop-filter:blur(12px);border-bottom:1px solid #1f2233}
nav{display:flex;justify-content:space-between;align-items:center;padding:1rem 0}
.logo{font-size:1.7rem;font-weight:700;color:var(--primary)}
nav ul{list-style:none;display:flex;gap:1.5rem;align-items:center}
nav ul li a{font-weight:500}
nav ul li a.active,nav ul li a:hover{color:var(--primary)}


section{padding:6rem 0}
.section-title{text-align:center;font-size:2.6rem;margin-bottom:3rem}

#hero{min-height:100vh;display:flex;align-items:center;padding-top:6rem}
.hero-grid{display:grid;grid-template-columns:1.2fr .8fr;gap:2.5rem;align-items:center}
#hero h1{font-size:3.6rem;margin:0}
#hero span{color:var(--primary)}
#typed{font-size:1.25rem;color:var(--muted)}
.cta{display:inline-flex;align-items:center;gap:.6rem;margin-top:2rem;padding:.9rem 2.3rem;border-radius:40px;background:linear-gradient(135deg,var(--primary),#4fbcd3);color:#000;font-weight:600;box-shadow:0 10px 30px rgba(105,210,231,.35)}
.avatar{width:210px;border-radius:8px;box-shadow:0 0 40px rgba(105,210,231,.45)}

.about-card{max-width:900px;margin:auto;background:linear-gradient(145deg,#14182a,#0f1220);padding:3rem;border-radius:22px;text-align:center}
.about-card p{font-size:1.1rem;line-height:1.9;color:var(--muted)}

.skills-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:2rem;max-width:1000px;margin:auto}
.skill-card{background:linear-gradient(145deg,#14182a,#1a1f33);padding:2rem;border-radius:20px;transition:.4s}
.skill-card:hover{transform:translateY(-10px);box-shadow:0 25px 50px rgba(105,210,231,.35)}
.skill-card h3{color:var(--primary)}
.skill-badge{display:inline-block;margin:.3rem .3rem .3rem 0;padding:.35rem .9rem;border-radius:20px;font-size:.75rem;background:#23284a;color:var(--primary)}

.projects{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:2rem}
.project{background:var(--card);padding:1.8rem;border-radius:18px;cursor:pointer;transition:.4s}
.project:hover{transform:translateY(-10px);box-shadow:0 25px 50px rgba(105,210,231,.35)}
.project h3{color:var(--primary)}
.project .tech{font-size:.85rem;color:var(--primary);margin-top:.8rem}
.project .tech span{display:inline-block;background:#23284a;padding:.25rem .7rem;border-radius:12px;margin-right:.5rem;margin-bottom:.5rem}
.project .desc{color:var(--muted);font-size:.95rem;margin-top:.5rem}

.modal{position:fixed;inset:0;background:rgba(0,0,0,.7);display:none;align-items:center;justify-content:center;z-index:3000}
.modal-content{background:var(--card);max-width:800px;width:90%;padding:2.5rem;border-radius:20px;animation:pop .4s ease}
.close{float:right;cursor:pointer;font-size:1.4rem;color:var(--primary)}
@keyframes pop{from{transform:scale(.85);opacity:0}to{transform:scale(1);opacity:1}}

.timeline{max-width:900px;margin:auto}
.timeline-item{background:linear-gradient(145deg,#14182a,#1a1f33);padding:1.8rem;border-radius:18px;margin-bottom:1.6rem}
.timeline-item h4{color:var(--primary)}

.links-grid{display:flex;flex-wrap:wrap;justify-content:center;gap:1.2rem}
.profile-link{padding:.8rem 1.6rem;border-radius:30px;background:#1e2442;color:var(--primary);font-weight:600}
.profile-link:hover{background:var(--primary);color:#000}

#contact{text-align:center}
#contact a{font-size:1.8rem;margin:0 .9rem;color:var(--primary)}
footer{text-align:center;padding:2rem;color:#6f75a3}

@media(max-width:768px){.hero-grid{grid-template-columns:1fr;text-align:center}#hero h1{font-size:2.6rem}}
</style>
</head>
<body>
<div id="progress"></div>
<header>
  <nav class="container">
    <div class="logo">Dharshini</div>
    <ul>
      <li><a href="#hero" class="active">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#internship">Internship</a></li>
      <li><a href="#certifications">Certifications</a></li>
      <li><a href="#achievements">Achievements</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
</header>

<section id="hero">
  <div class="container hero-grid">
    <div>
      <h1>Hello, I'm <span>Dharshini S</span></h1>
      <p id="typed"></p>
      <a href="Resume Updated (2).pdf" class="cta" download><i class="fa-solid fa-download"></i> Download Resume</a>
    </div>
    <div style="text-align:center"><img src="727823TUCS046.jpg" class="avatar"></div>
  </div>
</section>

<section id="about"><h2 class="section-title">About Me</h2><div class="about-card"><p>I'm a Computer Science Engineering student with a passion for building scalable, user-centric applications. With hands-on experience in full-stack development using Java, Spring Boot, and React, I excel at transforming ideas into robust solutions. I'm driven by continuous learning, clean code principles, and creating technologies that make a real impact. When I'm not coding, you'll find me exploring new frameworks, contributing to open-source projects, or diving into emerging technologies in cloud computing and AI/ML.</p></div></section>

<section id="skills"><h2 class="section-title">Skills</h2><div class="container skills-grid">
<div class="skill-card"><h3>Frontend Development</h3><span class="skill-badge">React</span><span class="skill-badge">HTML5</span><span class="skill-badge">CSS3</span><span class="skill-badge">JavaScript</span><span class="skill-badge">Responsive Design</span></div>
<div class="skill-card"><h3>Backend Development</h3><span class="skill-badge">Java</span><span class="skill-badge">Spring Boot</span><span class="skill-badge">REST API</span><span class="skill-badge">Microservices</span><span class="skill-badge">Node.js</span></div>
<div class="skill-card"><h3>Databases</h3><span class="skill-badge">SQL</span><span class="skill-badge">MySQL</span><span class="skill-badge">MongoDB</span><span class="skill-badge">Database Design</span></div>
<div class="skill-card"><h3>Tools & Platforms</h3><span class="skill-badge">Git</span><span class="skill-badge">GitHub</span><span class="skill-badge">Maven</span><span class="skill-badge">VS Code</span><span class="skill-badge">AWS</span></div>
<div class="skill-card"><h3>Programming Languages</h3><span class="skill-badge">Java</span><span class="skill-badge">C++</span><span class="skill-badge">Python</span><span class="skill-badge">JavaScript</span></div>
<div class="skill-card"><h3>Software & Concepts</h3><span class="skill-badge">OOP</span><span class="skill-badge">Data Structures</span><span class="skill-badge">Algorithms</span><span class="skill-badge">System Design</span><span class="skill-badge">UX/UI</span></div>
</div></section>

<section id="projects"><h2 class="section-title">Projects</h2><div class="container projects">
<div class="project" onclick="openModal('expense')"><h3>Expense Splitter</h3><p class="desc">Group expense sharing application with split calculations and payment tracking</p><div class="tech"><span>React</span><span>Spring Boot</span><span>REST API</span></div></div>
<div class="project" onclick="openModal('stock')"><h3>Stock Management System</h3><p class="desc">Comprehensive inventory dashboard with real-time stock tracking and updates</p><div class="tech"><span>React</span><span>Java</span><span>SQL</span></div></div>
<div class="project" onclick="openModal('festival')"><h3>Music Festival Organizer</h3><p class="desc">Event management backend for scheduling artists, venues, and attendee management</p><div class="tech"><span>Spring Boot</span><span>REST API</span><span>Database</span></div></div>
<div class="project" onclick="openModal('movie')"><h3>Movie Discovery</h3><p class="desc">Interactive app using TMDB API for exploring movies, ratings, and recommendations</p><div class="tech"><span>React</span><span>TMDB API</span><span>JavaScript</span></div></div>
<div class="project" onclick="openModal('wander')"><h3>Wanderwise Travel</h3><p class="desc">Travel discovery platform with destination guides, itineraries, and travel tips</p><div class="tech"><span>React</span><span>Node.js</span><span>MongoDB</span></div></div>
</div></section>

<section id="internship"><h2 class="section-title">Internship</h2><div class="timeline"><div class="timeline-item"><h4>Data Analytics Intern – LocknLog</h4><p>Java-based data processing and analysis.</p></div></div></section>

<section id="certifications"><h2 class="section-title">🏆 Certifications</h2><div class="container" style="max-width:900px"><div style="display:flex;flex-direction:column;gap:1.2rem">
<div class="cert-card" onclick="openCertModal('aws')" style="background:linear-gradient(145deg,#14182a,#1a1f33);padding:1.5rem;border-radius:18px;cursor:pointer;transition:.4s;hover{box-shadow:0 10px 30px rgba(105,210,231,.35)}"><p style="margin:0;color:var(--text);font-weight:600">✅ AWS Cloud Practitioner Essentials</p><p style="margin:.3rem 0 0 0;color:var(--muted);font-size:.9rem">Amazon Web Services Certification</p><p style="margin:.5rem 0 0 0;color:var(--primary);font-size:.8rem">Click to view certificate</p></div>
<div class="cert-card" onclick="openCertModal('nptel')" style="background:linear-gradient(145deg,#14182a,#1a1f33);padding:1.5rem;border-radius:18px;cursor:pointer;transition:.4s"><p style="margin:0;color:var(--text);font-weight:600">✅ NPTEL – Machine Learning, AI, Effective Writing</p><p style="margin:.3rem 0 0 0;color:var(--muted);font-size:.9rem">Indian Institute of Technology Certification</p><p style="margin:.5rem 0 0 0;color:var(--primary);font-size:.8rem">Click to view certificate</p></div>
<div class="cert-card" onclick="openCertModal('coursera')" style="background:linear-gradient(145deg,#14182a,#1a1f33);padding:1.5rem;border-radius:18px;cursor:pointer;transition:.4s"><p style="margin:0;color:var(--text);font-weight:600">✅ Coursera – AI, OOP Design, UX Design, Network Security</p><p style="margin:.3rem 0 0 0;color:var(--muted);font-size:.9rem">Multiple Specializations</p><p style="margin:.5rem 0 0 0;color:var(--primary);font-size:.8rem">Click to view certificate</p></div>
<div class="cert-card" onclick="openCertModal('cisco')" style="background:linear-gradient(145deg,#14182a,#1a1f33);padding:1.5rem;border-radius:18px;cursor:pointer;transition:.4s"><p style="margin:0;color:var(--text);font-weight:600">✅ Cisco – Python Essentials, Cybersecurity</p><p style="margin:.3rem 0 0 0;color:var(--muted);font-size:.9rem">Cisco Networking Academy</p><p style="margin:.5rem 0 0 0;color:var(--primary);font-size:.8rem">Click to view certificate</p></div>
<div class="cert-card" onclick="openCertModal('infosys')" style="background:linear-gradient(145deg,#14182a,#1a1f33);padding:1.5rem;border-radius:18px;cursor:pointer;transition:.4s"><p style="margin:0;color:var(--text);font-weight:600">✅ Infosys Springboard – React & UI/UX</p><p style="margin:.3rem 0 0 0;color:var(--muted);font-size:.9rem">Front-end Development Specialization</p><p style="margin:.5rem 0 0 0;color:var(--primary);font-size:.8rem">Click to view certificate</p></div>
</div></div></section>

<section id="achievements"><h2 class="section-title">🥇 Achievements & Participations</h2><div class="container" style="max-width:900px"><div style="display:flex;flex-direction:column;gap:1.2rem">
<div style="background:linear-gradient(145deg,#1a1f33,#14182a);padding:1.5rem;border-radius:18px;border-left:4px solid var(--primary)"><p style="margin:0;color:var(--text);font-weight:600">🏆 Smart India Hackathon – College Level Selected</p><p style="margin:.3rem 0 0 0;color:var(--muted);font-size:.9rem">Nationwide Innovation Challenge</p></div>
<div style="background:linear-gradient(145deg,#1a1f33,#14182a);padding:1.5rem;border-radius:18px;border-left:4px solid var(--primary)"><p style="margin:0;color:var(--text);font-weight:600">🏆 IEEE Hackathon Participant</p><p style="margin:.3rem 0 0 0;color:var(--muted);font-size:.9rem">Institute of Electrical and Electronics Engineers Event</p></div>
<div style="background:linear-gradient(145deg,#1a1f33,#14182a);padding:1.5rem;border-radius:18px;border-left:4px solid var(--primary)"><p style="margin:0;color:var(--text);font-weight:600">🏆 SHE Codes Hackathon</p><p style="margin:.3rem 0 0 0;color:var(--muted);font-size:.9rem">Women-Focused Tech Initiative</p></div>
<div style="background:linear-gradient(145deg,#1a1f33,#14182a);padding:1.5rem;border-radius:18px;border-left:4px solid var(--primary)"><p style="margin:0;color:var(--text);font-weight:600">🏆 Hacksprint 2.0 – Iamneo</p><p style="margin:.3rem 0 0 0;color:var(--muted);font-size:.9rem">Competitive Programming Challenge</p></div>
</div></div></section>

<section id="contact"><h2 class="section-title">Contact</h2>
<a href="mailto:dharshinisamy723@gmail.com"><i class="fa-solid fa-envelope"></i></a>
<a href="https://github.com/Dharshini888" target="_blank"><i class="fa-brands fa-github"></i></a>
<a href="https://www.linkedin.com/in/s-dharshini2403/" target="_blank"><i class="fa-brands fa-linkedin"></i></a>
</section>

<footer>© 2026 Dharshini S | Premium Portfolio</footer>

<div class="modal" id="modal"><div class="modal-content"><span class="close" onclick="closeModal()">✖</span><h2 id="mTitle"></h2><p id="mDesc"></p><a id="mLink" class="cta" target="_blank">View GitHub</a></div></div>

<div class="modal" id="certModal"><div class="modal-content"><span class="close" onclick="closeCertModal()">✖</span><h2 id="cTitle"></h2><div id="cContent" style="text-align:center;margin:2rem 0"><img id="cImage" style="max-width:100%;height:auto;border-radius:12px;max-height:400px"></div><p id="cDesc" style="color:var(--muted);margin:.5rem 0"></p></div></div>

<script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>
<script>
new Typed('#typed',{strings:["Full Stack Developer | Java | Spring Boot | React","Building scalable software","Clean code enthusiast"],typeSpeed:45,backSpeed:25,loop:true});

window.addEventListener('scroll',()=>{const h=document.documentElement;document.getElementById('progress').style.width=(h.scrollTop/(h.scrollHeight-h.clientHeight))*100+'%'});document.querySelectorAll('nav ul li a').forEach(link=>{link.classList.remove('active');});document.querySelector('nav ul li a[href="#hero"]').classList.add('active');

const data={
expense:{t:'Expense Splitter',d:'Full-stack expense sharing application with split calculations and payment tracking. Features group management, expense categorization, and automated settlement calculations.',l:'https://github.com/iamneo-production/5c02fcf1-390a-4a11-977f-fcc2fac766f9-a7d37415-62cc-4be2-80c0-e40346acc2f5'},
stock:{t:'Stock Management System',d:'Comprehensive React-based inventory dashboard with real-time stock tracking, updates, and analytics. Manage products, quantities, and generate inventory reports.',l:'https://github.com/Dharshini888/Stock-Management-System-using-React'},
festival:{t:'Music Festival Organizer',d:'Spring Boot event management backend for scheduling artists, venues, and attendee management. Features event creation, artist booking, and attendance tracking.',l:'https://github.com/Dharshini888/A-Music-Festival-Organizer'},
movie:{t:'Movie Discovery',d:'Interactive entertainment app using TMDB API for exploring movies, ratings, and recommendations. Browse genres, read reviews, and save favorites.',l:'https://github.com/Divyadharshini-SA/movie_discovery'},
wander:{t:'Wanderwise Travel',d:'Travel discovery platform with destination guides, itineraries, and travel tips. Plan trips, explore attractions, and get local recommendations.',l:'https://github.com/Dharshini888/Wanderwise-Travel'}
};

const certs={
aws:{t:'AWS Cloud Practitioner Essentials',d:'Amazon Web Services Certification',i:''},
nptel:{t:'NPTEL – Machine Learning, AI, Effective Writing',d:'Indian Institute of Technology Certification',i:''},
coursera:{t:'Coursera – AI, OOP Design, UX Design, Network Security',d:'Multiple Specializations',i:''},
cisco:{t:'Cisco – Python Essentials, Cybersecurity',d:'Cisco Networking Academy',i:''},
infosys:{t:'Infosys Springboard – React & UI/UX',d:'Front-end Development Specialization',i:''}
};
function openModal(k){document.getElementById('mTitle').innerText=data[k].t;document.getElementById('mDesc').innerText=data[k].d;document.getElementById('mLink').href=data[k].l;document.getElementById('modal').style.display='flex'}
function closeModal(){document.getElementById('modal').style.display='none'}
function openCertModal(k){document.getElementById('cTitle').innerText=certs[k].t;document.getElementById('cDesc').innerText=certs[k].d;const img=document.getElementById('cImage');if(certs[k].i){img.src=certs[k].i;img.style.display='block'}else{img.style.display='none';document.getElementById('cContent').innerHTML='<div style="padding:3rem;text-align:center;color:var(--muted)"><p style="font-size:1rem">Certificate image coming soon...</p><p style="font-size:.9rem;margin-top:.5rem">You can add your certificate by updating the image URL in the data</p></div>'}document.getElementById('certModal').style.display='flex'}
function closeCertModal(){document.getElementById('certModal').style.display='none'}
window.onclick=function(event){if(event.target==document.getElementById('modal'))closeModal();if(event.target==document.getElementById('certModal'))closeCertModal();}
</script>
</body>
</html>
