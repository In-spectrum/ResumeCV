---
layout: default
title: Portfolio
---

## 🚀 Портфоліо

# Олександр Дерик
---

## 🧩 Оптико-електронна тепловізійна системою відеоспостереження

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
Система призначена для відео спостереження, в ***денний та нічний*** час, за об’єктами, місцевістю на відстанях понад 30км. Забезпечує: автоматизоване спостереження за визначеними секторами, лазерне вимірювання відстані до об’єкта, фото/відео фіксацію, автоматичне виявлення об’єктів та їх супровід. Управління здійснюється за допомогою окремого пульта управлінн або зі стаціонарного ПК, планшета по Ethernet(WiFi) мережі.

**Розробив**  
Додаток користувача для управління системою на платформі: Windows,  Ubuntu, ARM (NVIDIA Jetson TX2), Android.

**Технології**  
`С++` · `Qt(QML)` · `Multithreading` · `TCP/IP` · `онлай/офлайн карти місцемості EspiMap` · `навігація GPS` · `Serial-port` · `Pelco-D` · `натівний протокол управління поворотною системою` · `зум/фокус оптичної системи` · `GStreamer (RTP/RTSP-stream, запис відео, запис екрана)`

---

## 🧩 Балістичний калькулятор

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
Android додаток для управління оптичним тепловізійним прицілом. Забезпечує: управління прицілом зі смартфона, обмін файлами(профілями) налаштувань, отримання результатів вимірювання відстані до цілі та відображає її на мапі місцевості. Управління забезпечується по BluetoothLE мережі. За допомогою WiFi – на смартфоні здійснюється перегляд поточного відео з прицілу, а також його фото/відео фіксація.

**Розробив**  
Архітектуру додатку, програмне забезпечення. Здійснив тестування та публікацію додатку.

**Технології**  
`Java` · `Multithreading` · `TCP/IP` · `BluetoothLE` · `HERE Map SDK` · `GStreamer (JPEG-stream, фото та відео запис)`

---

## 🧩 Тепловізійний розвідувальний прилад

<p align="center">
  <a href="images/app2_1.png" target="_blank">
    <img src="images/app2_1.png" height="250">
  </a>
</p>

**Опис**  
Оптичний прилад для ведення розвідки за допомогою тепловізійного та денного відеоканалів.  
Здійснює: прив’язку до місцевості по GPS або ручному вводу координат, лазерний замір відстані до цілі, запис двоканального відео,  
трансляцію відео та передачу поточних даних в мережу.

**Розробив**  
Архітектуру та програмне забезпечення “меню користувача”,  
управління приладом з використанням зовнішніх елементів (кнопки, джойстик)  
для вбудованої системи (платформа HiSilicon “HIVIEW-TECH”)

**Технології**  
`С` · `Embedded systems` · `Qt` · `Multithreading` · `TCP/IP` · `LVGL` · `JSON` · `I2C`

---

## 🧩  <a href="https://in-spectrum.github.io/BypassNAT/" target="_blank">BypassNAT | System for remote access to devices</a>

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
- налаштування ssh-тунелю, доступ до пристроїв за допомогою ssh-протоколу;

Підтримує платформи: Windows, Ubuntu, ARM (Raspberry Pi), Android

**Технології**  
`С++` · `Qt(QML)` · `Multithreading` · `TCP/IP` · `GStreamer (RTSP/RTMP-stream)` · `MediaMTX``  

<a href="https://github.com/In-spectrum/BypassNAT" target="_blank">GitHub</a>

---

## 🧩  <a href="https://in-spectrum.github.io/CamOnTime/" target="_blank">CamOnTime | Personal media service</a>

<p align="center">
  <a href="https://in-spectrum.github.io/CamOnTime/manual/videos/demo.mp4">
    <img src="https://in-spectrum.github.io/CamOnTime/manual/images/demo_preview.png" width="400">
  </a>
</p>

**Опис**  
Кросплатформений ***особистий*** мультимедійний сервіс (клієнт/rtsp-сервер), який забезпечує:
- реєстрацію ip-камер;
- перегляд відео з ip-камер;
- збереження відео на сервері;
- перегляд відофайлів;

Підтримує платформи: Windows, Ubuntu, ARM (Raspberry Pi), Android.  

**Технології**  
`C++` · `Qt(QML)` · `TCP/IP` · `GStreamer(RTSP-stream, RTSP-server)`  

<a href="https://github.com/In-spectrum/CamOnTime" target="_blank">GitHub</a>

---

## 🧩 Mean Mole

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
