---
layout: default
title: "Портфоліо"
---

<h2 style="text-align:right; border:none; margin-bottom:0;">
  🌐 <a href="index.html">EN</a>
</h2>

<h1 style="margin-top:0; font-size:2.5em;">
  Олександр Дерик
</h1>

<h2 style="border:none; margin-bottom:0;">
  🚀 Портфоліо
</h2>

* [**BypassNAT (система віддаленого доступ до приладів)**](#app_4)
* [**CamOnTime (особистий медіа сервіс)**](#app_5)
* [**Оптико-електронна тепловізійна система відеоспостереження**](#app_1)
* [**Балістичний калькулятор**](#app_2)
* [**Тепловізійний розвідувальний приладv**](#app_3)
* [**Mean Mole (game)**](#app_6)
* [**IP-cam GO**](#app_7)

---

<h2 id="app_4">
	🧩  <a href="https://in-spectrum.github.io/BypassNAT/" target="_blank">BypassNAT | System for remote access to devices</a>
</h2>


<p align="center">
  <a href="https://in-spectrum.github.io/BypassNAT/" target="_blank">
    	<img src="https://in-spectrum.github.io/BypassNAT/manual/images/baner.png" width="500" style="height:auto;"
        alt="BypassNAT | System for remote access to devices.">
	</a>
</p>

**Опис**  
Кросплатформена система (клієнт/сервер) для віддаленого управління комп'ютером, пристроями,  
які розташовані у мережі, де використовується NAT.  

Забезпечує:
- використання ***особистого*** сервера для збереження конфіденційності: 
- віддалене керування пристроями;
- обмін файлами;
- захоплення, трансляція та перегляд робочого столу;
- налаштування ssh-тунелю, доступ до пристроїв за допомогою ssh-протоколу.

Підтримує платформи: Windows, Ubuntu, ARM (Raspberry Pi), Android

**Технології**  
С++, Qt(QML), Multithreading, TCP/IP, 
<a href="https://mediamtx.org/docs/kickoff/introduction" target="_blank">MediaMTX</a>, 
<a href="https://nginx.org/" target="_blank">Nginx</a>, 
<a href="https://gstreamer.freedesktop.org/" target="_blank">GStreamer</a> (RTSP/RTMP-stream)

<a href="https://github.com/In-spectrum/BypassNAT" target="_blank">GitHub</a>

---

<h2 id="app_5">
	🧩  <a href="https://in-spectrum.github.io/CamOnTime/" target="_blank">CamOnTime | Personal media service</a>
</h2>

<p align="center">
  <b>Video preview</b>
</p>
<p align="center">
  <a href="https://in-spectrum.github.io/CamOnTime/manual/videos/demo.mp4"
     style="position:relative; display:inline-block;">
    <img src="https://in-spectrum.github.io/CamOnTime/manual/images/demo_preview.png"  width="400" style="height:auto;">	  
  </a>	
</p>



**Опис**  
Кросплатформений ***особистий*** мультимедійний сервіс (клієнт/rtsp-сервер).  
  
Забезпечує:
- реєстрацію ip-камер;
- перегляд відео з ip-камер;
- збереження відео на сервері;
- перегляд відофайлів;
- копіювання відеофайлів з сервера на смартфон;
- надання доступу до камери іншим користувачам.

Підтримує платформи: Windows, Ubuntu, ARM (Raspberry Pi), Android.  

**Технології**  
C++, Qt(QML), TCP/IP, 
<a href="https://gstreamer.freedesktop.org/" target="_blank">GStreamer</a> (RTSP-stream, RTSP-server)  

<a href="https://github.com/In-spectrum/CamOnTime" target="_blank">GitHub</a>

---

<h2 id="app_1">🧩 Оптико-електронна тепловізійна система відеоспостереження</h2>

<p align="center">
  <a href="images/app1_1.jpg" target="_blank">
    <img src="images/app1_1.jpg" width="500" style="height:auto;">
  </a>
</p>
<p align="center">
  <a href="images/app1_2.jpg" target="_blank">
    <img src="images/app1_2.jpg" width="600" style="height:auto;">
  </a>
</p>

**Опис**  
Система призначена для відео спостереження, в ***денний та нічний*** час, за місцевістю та об’єктами на відстанях понад 30км. 
  
Забезпечує:
- автоматизоване спостереження за визначеними секторами;
- лазерне вимірювання відстані до об’єкта;
- фото/відео фіксацію;
- автоматичне виявлення об’єктів та їх супровід.

Управління здійснюється за допомогою окремого пульта управлінн або зі стаціонарного ПК, планшета по Ethernet(WiFi) мережі.

**Розробив**  
Додаток користувача для управління системою на платформі: Windows,  Ubuntu, ARM (NVIDIA Jetson TX2), Android.

**Технології**  
С++, Qt(QML), Multithreading, TCP/IP, 
онлай/офлайн карти місцемості EspiMap, 
навігація GPS, Serial-port, Pelco-D, натівний протокол управління поворотною системою, зум/фокус оптичної системи, 
<a href="https://gstreamer.freedesktop.org/" target="_blank">GStreamer</a> (RTP/RTSP-stream, запис відео, запис екрана)

---

<h2 id="app_2">🧩 Балістичний калькулятор</h2>

<p align="center">
  <a href="images/app2_1.jpg" target="_blank">
    <img src="images/app2_1.jpg" width="400" style="height:auto;">
  </a>
</p>
<p align="center">
  <a href="images/app2_3.jpg" target="_blank">
    <img src="images/app2_3.jpg" width="500" style="height:auto;">
  </a>
</p>

<div style="text-align:center; margin:10px 0;">
  
  <a href="images/app2_4.jpg" target="_blank" style="display:inline-block;">
    <img src="images/app2_4.jpg"
         style="height:400px; width:auto; margin:5px 5px; border-radius:6px;">
  </a>

  <a href="images/app2_2.jpg" target="_blank" style="display:inline-block;">
    <img src="images/app2_2.jpg"
         style="height:400px; width:auto; margin:5px 5px; border-radius:6px;">
  </a>

</div>

**Опис**  
Android додаток для управління оптичним тепловізійним прицілом.  
  
Забезпечує:
- перегляд на смартфоні поточного відео з прицілу;
- запис на смартфоні фото/відео файлів;
- управління прицілом зі смартфона;
- обмін файлами(профілями) налаштувань;
- лазерне вимірювання відстані до об’єкта;
- відображення координат об’єкта на мапі місцевості.

Управління забезпечується по BluetoothLE, робота з відео по WiFi.  

**Розробив**  
Архітектуру додатку та програмне забезпечення. Здійснив тестування та публікацію додатку.

**Технології**  
Java, Multithreading, TCP/IP, BluetoothLE, 
<a href="https://www.here.com/docs/category/here-sdk-android" target="_blank">HERE Map SDK</a>, 
<a href="https://gstreamer.freedesktop.org/" target="_blank">GStreamer</a> (JPEG-stream, фото та відео запис)

---

<h2 id="app_3">🧩 Тепловізійний розвідувальний прилад</h2>

<p align="center">
  <a href="images/app3_1.jpg" target="_blank">
    <img src="images/app3_1.jpg"  width="350" style="height:auto;">
  </a>
</p>
<p align="center">
  <a href="images/app3_2.jpg" target="_blank">
    <img src="images/app3_2.jpg" width="500" style="height:auto;">
  </a>
</p>

**Опис**  
Оптичний прилад для ведення розвідки за допомогою тепловізійного та денного відеоканалів.  
  
Забезпечує:
- прив’язку до місцевості по GPS або ручному вводу координат;
- лазерне вимірювання відстані до об’єкта;
- передачу поточних даних в мережу.
- запис двоканального відео; 
- трансляцію відео по rtsp-протоколу.

**Розробив**  
Архітектуру та програмне забезпечення “меню користувача, OSD”,  
управління приладом з використанням зовнішніх елементів (кнопки, джойстик)  
для вбудованої системи (платформа HiSilicon <a href="https://github.com/openhisilicon/HIVIEW" target="_blank">“HIVIEW-TECH”</a>)

**Технології**  
С, Embedded systems, Qt, Multithreading, TCP/IP, 
<a href="https://lvgl.io/" target="_blank">LVGL</a>, 
JSON, I2C

---

<h2 id="app_6">
	🧩  <a href="https://www.amazon.co.jp/-/en/dp/B0777TMJS3" target="_blank">Mean Mole</a>
</h2>
		
<p align="center">
  <a href="images/app4_1.jpg" target="_blank">
    <img src="images/app4_1.jpg"  width="350" style="height:auto;">
  </a>
</p>

<div style="text-align:center; margin:10px 0;">
  
  <a href="images/app4_2.jpg" target="_blank" style="display:inline-block;">
    <img src="images/app4_2.jpg"
         style="width:400px; height:auto; margin:5px 5px; border-radius:6px;">
  </a>

  <a href="images/app4_3.jpg" target="_blank" style="display:inline-block;">
    <img src="images/app4_3.jpg"
         style="width:400px; height:auto; margin:5px 5px; border-radius:6px;">
  </a>

</div>

**Опис**  
Кросплатформений ігровий додаток у якому потрібно подолати перешкоди  
та засіяти визначену ділянку землі.  
Розроблено для платфом: Windows, Ubuntu, Android, iOs, Windows Phone.

**Розробив**  
Архітектуру, логіку та програмне забезпечення.

**Технології**  
С++, Qt(QML)

---

<h2 id="app_7">🧩 IP-cam GO</h2>

<div style="text-align:center; margin:10px 0;">
  
  <a href="images/app5_1.jpg" target="_blank" style="display:inline-block;">
    <img src="images/app5_1.jpg"
         style="height:400px; width:auto; margin:5px 5px; border-radius:6px;">
  </a>

  <a href="images/app5_2.jpg" target="_blank" style="display:inline-block;">
    <img src="images/app5_2.jpg"
         style="height:400px; width:auto; margin:5px 5px; border-radius:6px;">
  </a>

  <a href="images/app5_3.jpg" target="_blank" style="display:inline-block;">
    <img src="images/app5_3.jpg"
         style="height:400px; width:auto; margin:5px 5px; border-radius:6px;">
  </a>

</div>

<div style="text-align:center; margin:10px 0;">
 
  <a href="images/app5_4.jpg" target="_blank" style="display:inline-block;">
    <img src="images/app5_4.jpg"
         style="height:400px; width:auto; margin:5px 5px; border-radius:6px;">
  </a>

  <a href="images/app5_5.jpg" target="_blank" style="display:inline-block;">
    <img src="images/app5_5.jpg"
         style="height:400px; width:auto; margin:5px 5px; border-radius:6px;">
  </a>

</div>

**Опис**  
Андроїд додаток для мультимедійної системи.
 
Забезпечує:
- підключення ip-камер до сервера;
- управління та налаштування ip-камер на сервері;
- перегляд поточного відео з ip-камер;
- перегляд архіву відео;
- збереження на смартфон фото/відео файлів;
- оплату послуг.

**Розробив**  
Логіку та програмне забезпечення.

**Технології**  
Java, Multithreading, REST API

---

