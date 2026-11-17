<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>e-Portfolio | มิ่งขวัญ ประดิษฐ์ผล</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Sans+Thai:wght@400;600;700&display=swap" rel="stylesheet">
<style>
:root{--bg:#f6f8fb;--ink:#14213d;--muted:#55607a;--line:#d5dbe8;--accent:#1d4ed8;--card:#fff}
@media (prefers-color-scheme:dark){:root{--bg:#0e1424;--ink:#eef2fb;--muted:#a3adc6;--line:#27304a;--accent:#7aa2ff;--card:#161e34}}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
@media (prefers-reduced-motion:reduce){html{scroll-behavior:auto}}
body{margin:0;font-family:"IBM Plex Sans Thai",system-ui,sans-serif;background:var(--bg);color:var(--ink);line-height:1.75}
a{color:var(--accent)}
a:focus-visible{outline:3px solid var(--accent);outline-offset:3px}
.layout{display:grid;grid-template-columns:280px 1fr;max-width:1040px;margin:0 auto}
aside{position:sticky;top:0;height:100vh;padding:48px 28px;border-right:1px solid var(--line)}
.avatar{width:112px;height:112px;border-radius:50%;background:var(--accent);color:#fff;display:grid;place-items:center;font-size:44px;font-weight:700;overflow:hidden;position:relative}
.avatar img{position:absolute;inset:0;width:100%;height:100%;object-fit:cover}
aside h1{font-size:1.5rem;margin:20px 0 4px;line-height:1.3}
aside p{margin:0;color:var(--muted)}
nav{margin-top:32px;display:flex;flex-direction:column;gap:4px}
nav a{padding:8px 0;text-decoration:none;color:var(--ink);font-weight:600;border-bottom:1px solid var(--line)}
nav a:hover{color:var(--accent)}
main{padding:48px 40px 80px}
section{margin-bottom:64px;scroll-margin-top:24px}
h2{font-size:1.75rem;margin:0 0 16px}
.lead{font-size:1.25rem;max-width:60ch}
p{max-width:65ch}
.skills{display:flex;flex-wrap:wrap;gap:8px;padding:0;list-style:none}
.skills li{border:1.5px solid var(--accent);color:var(--accent);padding:4px 14px;border-radius:999px;font-weight:600}
.work{background:var(--card);border:1px solid var(--line);border-radius:12px;padding:24px;margin-bottom:16px}
.work h3{margin:0 0 4px}
.work .tag{color:var(--muted);font-size:.95rem}
.btn{display:inline-block;margin-top:8px;padding:8px 18px;background:var(--accent);color:#fff;border-radius:8px;text-decoration:none;font-weight:600}
@media (prefers-color-scheme:dark){.btn{color:#0e1424}}
@media (max-width:760px){
 .layout{grid-template-columns:1fr}
 aside{position:static;height:auto;border-right:0;border-bottom:1px solid var(--line);padding:32px 20px}
 nav{flex-direction:row;flex-wrap:wrap;gap:16px}
 nav a{border:0}
 main{padding:32px 20px 64px}
}
</style>
</head>
<body>
<div class="layout">
 <aside>
  <div class="avatar" aria-label="รูปโปรไฟล์">
   ส
   <!-- วางรูปของคุณที่ images/profile.jpg แล้วรูปจะแสดงทับตัวอักษร -->
   <img src="images/profile.jpg" alt="รูปโปรไฟล์ของ [มิ่งขวัญ ประดิษฐ์ผล]" onerror="this.remove()">
  </div>
  <h1>มิ่งขวัญ ประดิษฐ์ผล</h1>
  <p>นักเรียนชั้น มัธยมศึกษาปีที่6 โรงเรียน ธัญรัตน์</p>
  <nav aria-label="เมนูหลัก">
   <a href="#about">เกี่ยวกับฉัน</a>
   <a href="#skills">ทักษะ</a>
   <a href="#works">ผลงาน</a>
   <a href="#contact">ติดต่อ</a>
  </nav>
 </aside>

 <main>
  <section id="about">
   <h2>เกี่ยวกับฉัน</h2>
   <p class="lead">ตอนนี้เรียนอยู่ชั้นมัธยมศึกษาปีที่ 6 โรงเรียนธัญรัตน์ กำลังฝึกสร้างเว็บไซต์ด้วย HTML, CSS และ JavaScript และอยากพัฒนาทักษะนี้ต่อไป</p>
   <p>ฉันชื่อมิ่ง ชอบนอนและเล่นเกม ตอนนี้กำลังเรียนรู้การสร้างเว็บไซต์ อยากนำทักษะนี้ไปต่อยอดในการเรียนและการทำงานในอนาคต</p>
  </section>

  <section id="skills">
   <h2>ทักษะ</h2>
   <ul class="skills">
    <li>HTML</li><li>CSS</li><li>JavaScript เบื้องต้น</li><li>Git และ GitHub</li><li>การเล่นเกมเป็นทีม</li>
   </ul>
  </section>

  <section id="works">
   <h2>ผลงาน</h2>
   <article class="work">
    <h3>เครื่องคำนวณ BMI</h3>
    <p class="tag">HTML, CSS, JavaScript</p>
    <p>เว็บเล็ก ๆ ที่รับน้ำหนักและส่วนสูง แล้วคำนวณค่า BMI พร้อมบอกช่วงเกณฑ์</p>
    <a class="btn" href="projects/bmi.html">เปิดผลงาน</a>
    <a href="https://github.com/[username]/[repository]/blob/main/projects/bmi.html">ดูโค้ดบน GitHub</a>
   </article>
  </section>

  <section id="contact">
   <h2>ติดต่อ</h2>
   <p>อีเมล: <a href="mailto:example@email.com">chanitpolpuwieng6@email.com</a></p>
   <p>GitHub: <a href="https://github.com/chanitpol">github.com/chanitpol</a></p>
  </section>
 </main>
</div>
</body>
</html>
