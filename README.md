<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<script src="./support.js"></script>
</head>
<body>
<x-dc>
<helmet data-dc-atomics>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Newsreader:ital,opsz,wght@0,6..72,400;0,6..72,500;0,6..72,600;1,6..72,400;1,6..72,500&family=IBM+Plex+Mono:wght@400;500&display=swap" rel="stylesheet">
<link rel="icon" type="image/svg+xml" href="brand/gks-favicon.svg">
<style>body{margin:0;background:#f7f3ec} @keyframes gksSplash{0%,45%{opacity:1}100%{opacity:0;visibility:hidden}}</style>
</helmet>

<div style="position:fixed;inset:0;z-index:100;background:#f7f3ec;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:20px;pointer-events:none;animation:gksSplash 1.1s ease forwards">
  <div style="font-family:Georgia,serif;font-style:italic;font-size:64px;color:#221c18">GKS</div>
  <div style="width:88px;height:5px;background:#b03a2e"></div>
</div>

<div style="min-height:100vh;background:#f7f3ec;color:#221c18;font-family:'Newsreader',Georgia,serif" data-screen-label="Home">

  <div style="display:flex;justify-content:space-between;align-items:baseline;padding:26px 56px;border-bottom:1px solid #e0d8ca">
    <a href="Home.dc.html" style="font-size:17px;font-weight:600;font-style:italic;color:#221c18;text-decoration:none">Gabriel K. Staniszewski</a>
    <div style="display:flex;gap:26px;font:400 14px Helvetica,Arial,sans-serif">
      <a href="Home.dc.html" style="color:#221c18;text-decoration:none;border-bottom:1px solid oklch(0.5 0.16 25);padding-bottom:2px">Home</a>
      <a href="About.dc.html" style="color:#6b5f52;text-decoration:none">About</a>
      <a href="CV.dc.html" style="color:#6b5f52;text-decoration:none">CV</a>
      <a href="Portfolio.dc.html" style="color:#6b5f52;text-decoration:none">Portfolio</a>
      <a href="Blog.dc.html" style="color:#6b5f52;text-decoration:none">Blog</a>
      <a href="Contact.dc.html" style="color:#6b5f52;text-decoration:none">Contact</a>
    </div>
  </div>

  <div style="padding:88px 56px 60px;display:flex;flex-direction:column;gap:28px;align-items:center;text-align:center">
    <div style="font:500 12px 'IBM Plex Mono',monospace;letter-spacing:.14em;color:oklch(0.5 0.16 25)">FROM LUBLIN, OF BOSTON</div>
    <h1 style="margin:0;font-size:62px;font-weight:500;line-height:1.06;letter-spacing:-.01em;max-width:800px;text-wrap:balance">A future built one heartbeat at a time.</h1>
    <div style="font-size:20px;line-height:1.6;color:#5c5245;max-width:640px;font-style:italic;text-wrap:pretty">Medical student, aspiring cardiac surgeon, and grandson of people who refused to give up. I study the heart for the simplest reason there is: every beat counts.</div>
    <div style="display:flex;gap:16px;margin-top:8px;font-family:Helvetica,Arial,sans-serif">
      <a href="About.dc.html" style="padding:14px 30px;background:#221c18;color:#f7f3ec;font-size:14px;font-weight:600;text-decoration:none">My story</a>
      <a href="Portfolio.dc.html" style="padding:14px 30px;border:1px solid #c9bfae;color:#221c18;font-size:14px;font-weight:600;text-decoration:none">View portfolio</a>
    </div>
  </div>

  <div style="display:grid;grid-template-columns:400px 1fr;gap:56px;padding:24px 56px 72px;align-items:center;max-width:1200px;margin:0 auto;box-sizing:border-box">
    <img src="uploads/FullSizeRender-2.jpeg" alt="Gabriel Staniszewski" style="width:100%;aspect-ratio:4/5;object-fit:cover;object-position:50% 20%;background:#e0d8ca">
    <div style="display:flex;flex-direction:column;gap:28px">
      <div style="display:flex;flex-direction:column;gap:7px;border-bottom:1px solid #e0d8ca;padding-bottom:24px">
        <div style="font:600 13px Helvetica,Arial,sans-serif;color:oklch(0.5 0.16 25)">Research</div>
        <div style="font-size:26px;font-weight:500;line-height:1.2">Where fluid dynamics meets the failing artery</div>
        <div style="font:400 15px/1.65 Helvetica,Arial,sans-serif;color:#6b5f52;text-wrap:pretty">CFD modeling of arterial stenosis in high school — the project that set the course toward cardiovascular medicine.</div>
        <a href="Portfolio.dc.html" style="font:600 13px Helvetica,Arial,sans-serif;color:#221c18;text-decoration:none;margin-top:4px">Explore the research →</a>
      </div>
      <div style="display:flex;flex-direction:column;gap:7px;border-bottom:1px solid #e0d8ca;padding-bottom:24px">
        <div style="font:600 13px Helvetica,Arial,sans-serif;color:oklch(0.5 0.16 25)">Heritage</div>
        <div style="font-size:26px;font-weight:500;line-height:1.2">A lineage of resilience</div>
        <div style="font:400 15px/1.65 Helvetica,Arial,sans-serif;color:#6b5f52;text-wrap:pretty">Great-grandparents who fought for Poland; grandparents who outlasted communism. Their courage is my compass.</div>
        <a href="About.dc.html" style="font:600 13px Helvetica,Arial,sans-serif;color:#221c18;text-decoration:none;margin-top:4px">Read the story →</a>
      </div>
      <div style="display:flex;flex-direction:column;gap:7px">
        <div style="font:600 13px Helvetica,Arial,sans-serif;color:oklch(0.5 0.16 25)">Curriculum vitae</div>
        <div style="font-size:26px;font-weight:500;line-height:1.2">Shared personally, on request</div>
        <div style="font:400 15px/1.65 Helvetica,Arial,sans-serif;color:#6b5f52;text-wrap:pretty">Write to me and I'll send the full CV along with a proper hello.</div>
        <a href="CV.dc.html" style="font:600 13px Helvetica,Arial,sans-serif;color:#221c18;text-decoration:none;margin-top:4px">Request the CV →</a>
      </div>
    </div>
  </div>

  <a href="About.dc.html" style="display:block;position:relative;height:340px;overflow:hidden;text-decoration:none">
    <img src="uploads/IMG_7861.jpeg" alt="Lublin old town at night" style="width:100%;height:100%;object-fit:cover;object-position:50% 55%">
    <div style="position:absolute;inset:0;background:linear-gradient(0deg,rgba(16,12,10,.72) 0%,rgba(16,12,10,.15) 55%,rgba(16,12,10,0) 100%)"></div>
    <div style="position:absolute;left:56px;bottom:44px;display:flex;flex-direction:column;gap:10px;max-width:560px">
      <div style="font:500 11px 'IBM Plex Mono',monospace;letter-spacing:.14em;color:#e8c9c2">LUBLIN, POLAND</div>
      <div style="font-family:'Newsreader',Georgia,serif;font-size:34px;font-weight:500;line-height:1.15;color:#f7f3ec">The city where I'm learning medicine — and where my story began generations ago.</div>
    </div>
  </a>

  <div style="position:relative;height:220px;overflow:hidden">
    <img src="uploads/IMG_1703.jpeg" alt="Anatomical heart engraving" style="width:100%;height:100%;object-fit:cover;object-position:60% 40%">
    <div style="position:absolute;inset:0;background:linear-gradient(90deg,#f7f3ec 0%,rgba(247,243,236,0) 45%)"></div>
    <a href="Blog.dc.html" style="position:absolute;left:56px;top:50%;transform:translateY(-50%);display:flex;flex-direction:column;gap:8px;max-width:340px;text-decoration:none;color:#221c18">
      <div style="font:500 11px 'IBM Plex Mono',monospace;letter-spacing:.14em;color:oklch(0.5 0.16 25)">THE BLOG</div>
      <div style="font-family:'Newsreader',Georgia,serif;font-size:26px;font-weight:500;line-height:1.15">Notes on the heart — coming soon</div>
    </a>
  </div>

  <div style="display:flex;justify-content:space-between;align-items:center;padding:26px 56px;border-top:1px solid #e0d8ca;font:400 13px Helvetica,Arial,sans-serif;color:#8a7d6d">
    <span><span style="font-family:'Newsreader',Georgia,serif;font-style:italic;font-size:13px;color:#221c18">GKS — every beat counts.</span> &nbsp;·&nbsp; Lublin, Poland — <a href="mailto:staniszewski.gabriel.k@gmail.com" style="color:#8a7d6d">staniszewski.gabriel.k@gmail.com</a></span>
    <span style="display:flex;gap:18px">
      <a href="https://www.linkedin.com/in/gabriel-staniszewski-33a3a7256" style="color:#8a7d6d;text-decoration:none">LinkedIn</a>
      <a href="https://www.instagram.com/gabriel.is.up/" style="color:#8a7d6d;text-decoration:none">Instagram</a>
    </span>
  </div>
</div>

</x-dc>
</body>
</html>
