---
layout: default
title: Portfolio
---

<style>
.nav {
  display:flex;
  justify-content:space-between;
  align-items:center;
  margin-bottom:50px;
}

.nav a {
  text-decoration:none;
  margin-left:25px;
  font-weight:600;
  color:#0366d6;
}

.nav a:hover {
  text-decoration:underline;
}

.project {
  margin-bottom:60px;
}

.gallery {
  display:flex;
  overflow-x:auto;
  gap:15px;
  margin:15px 0;
}

.gallery img {
  width:500px;
  border-radius:10px;
  box-shadow:0 4px 10px rgba(0,0,0,0.15);
}
</style>

<div class="nav">
  <div>
    <h1 style="margin:0;">Alexandr Deryk</h1>
    <p style="margin:0; color:gray;">C++ / Qt Developer</p>
  </div>
  <div>
    <a href="index.md">Resume</a>
    <a href="portfolio.md">Portfolio</a>
  </div>
</div>

<div class="project">
<h2>RTSP Client (Qt + GStreamer)</h2>

<div class="gallery">
  <img src="images/rtsp1.png">
  <img src="images/rtsp2.png">
</div>

<p>
Desktop application for viewing RTSP streams with recording support.
Optimized pipeline configuration and stable long-term playback.
</p>

<p><strong>Technologies:</strong> C++, Qt, GStreamer</p>
</div>

<div class="project">
<h2>File Transfer System</h2>

<div class="gallery">
  <img src="images/file1.png">
  <img src="images/file2.png">
</div>

<p>
Client-server system for transmitting binary data in chunks over TCP.
Designed for reliable large file transfer.
</p>

<p><strong>Technologies:</strong> C++, Qt, TCP/IP</p>
</div>

<!-- Додай ще 4 проєкти аналогічно -->

<hr>

<h3>🧾 <a href="index.md">Back to Resume</a></h3>
