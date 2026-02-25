---
layout: default
title: Portfolio
---

# Олександр Дерик

## 🚀 Портфоліо

* [**Оптико-електронна тепловізійна системою відеоспостереження**](#app_1)
* [**Балістичний калькулятор**](#app_2)
* [**Тепловізійний розвідувальний приладv**](#app_3)
* [**BypassNAT (system for remote access to devices)**](#app_4)
* [**CamOnTime (personal media service)**](#app_5)
* [**Mean Mole (the game)**](#app_6)
* [**IP-cam GO**](#app_7)

---

<h2 id="app_1">🧩 Оптико-електронна тепловізійна системою відеоспостереження</h2>

<p align="center">
  <a href="images/app1_1.png" target="_blank">
    <img src="images/app1_1.png" height="250">
  </a>
</p>
<p align="center">
  <a href="images/app1_2.png" target="_blank">
    <img src="images/app1_2.png" height="250">
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
`С++` · `Qt(QML)` · `Multithreading` · `TCP/IP` · `онлай/офлайн карти місцемості EspiMap` · `навігація GPS` · `Serial-port` · `Pelco-D` · `натівний протокол управління поворотною системою` · `зум/фокус оптичної системи` · `GStreamer (RTP/RTSP-stream, запис відео, запис екрана)`

---

<h2 id="app_2">🧩 Балістичний калькулятор</h2>

<p align="center">
  <a href="images/app3_1.png" target="_blank">
    <img src="images/app3_1.png" height="350">
  </a>
</p>
<p align="center">
  <a href="images/app3_2.png" target="_blank">
    <img src="images/app3_2.png" height="350">
  </a>
</p>

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
`Java` · `Multithreading` · `TCP/IP` · `BluetoothLE` · `HERE Map SDK` · `GStreamer (JPEG-stream, фото та відео запис)`

---

<h2 id="app_3">🧩 Тепловізійний розвідувальний прилад</h2>

<p align="center">
  <a href="images/app2_1.png" target="_blank">
    <img src="images/app2_1.png" height="250">
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
Архітектуру та програмне забезпечення “меню користувача”,  
управління приладом з використанням зовнішніх елементів (кнопки, джойстик)  
для вбудованої системи (платформа HiSilicon “HIVIEW-TECH”)

**Технології**  
`С` · `Embedded systems` · `Qt` · `Multithreading` · `TCP/IP` · `LVGL` · `JSON` · `I2C`

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
`С++` · `Qt(QML)` · `Multithreading` · `TCP/IP` · `GStreamer (RTSP/RTMP-stream)` · `MediaMTX``  

<a href="https://github.com/In-spectrum/BypassNAT" target="_blank">GitHub</a>

---

<h2 id="app_5">
	🧩  <a href="https://in-spectrum.github.io/CamOnTime/" target="_blank">CamOnTime | Personal media service</a>
</h2>


<p align="center">
  <a href="https://in-spectrum.github.io/CamOnTime/manual/videos/demo.mp4">
    <img src="https://in-spectrum.github.io/CamOnTime/manual/images/demo_preview.png" width="400">
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
`C++` · `Qt(QML)` · `TCP/IP` · `GStreamer(RTSP-stream, RTSP-server)`  

<a href="https://github.com/In-spectrum/CamOnTime" target="_blank">GitHub</a>

---

<h2 id="app_6">🧩 Mean Mole</h2>

<p align="center">
  <a href="images/app2_1.png" target="_blank">
    <img src="images/app2_1.png" height="250">
  </a>
</p>

**Опис**  
Кросплатформений ігровий додаток у якому потрібно подолати перешкоди  
та засіяти визначену ділянку землі.  
Розроблено для платфом: Windows, Ubuntu, Android, iOs, Windows Phone.

**Розробив**  
Архітектуру, логіку та програмне забезпечення.

**Технології**  
`С++` · `Qt(QML)`

---

<h2 id="app_7">🧩 IP-cam GO</h2>

<p align="center">
  <a href="images/app2_1.png" target="_blank">
    <img src="images/app2_1.png" height="250">
  </a>
</p>

**Опис**  
Андроїд додаток для мультимедійної системи.
 
Забезпечує:
- підключення ip-камер до сервера;
- управління та налаштування ip-камер на сервері;
- перегляд поточного відео з ip-камер;
- перегляд архіву відео;
- збереження на смартфон фото/відео файлів.

**Розробив**  
Логіку та програмне забезпечення.

**Технології**  
`Java` · `Multithreading` · `REST API`

---
