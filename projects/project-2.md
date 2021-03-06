---
layout: project
type: project
image: images/app-square.png
title: แอพสุ่มรายการอาหาร
permalink: projects/random-menu
# All dates must be YYYY-MM-DD format!
date: 2016-12-15
labels:
  - MIT App Invertor
  - Firebase
summary: สร้างแอพพลิเคชั่นสุ่มรายการอาหารด้วยการเขย่า โดยใช้ MIT App Invertor
---

<img class="ui medium right floated rounded image" src="../images/preview-page.png">

แอพสุ่มรายการอาหารเป็นโปรเจคในช่วงผมศึกษาอยู่ชั้นปีที่ 2 โดย หัวข้อคือสร้างแอพลิเคชั่นบนโทรศัพท์มือถืออะไรก็ได้ โดยใช้ [MIT App Invertor](https://appinventor.mit.edu/)

### รายละการทำงานเอียดของโปรเจค

1.1 ส่วน Input
  * รับค่าการเขย่า


1.2 ส่วน Output
  * รูปภาพอาหาร
  * ราคาอาหาร
  * ชื่อร้านอาหาร


1.3 ส่วนของการทำงาน
  * ระบบจะทำการสุ่มอาหารพร้อมข้อมูลเบื้องต้นของอาหาร


แอพสุ่มรายการอาหารนี้มีการทำงานโดยการรับการเขย่าจากผู้ใช้งานทุกๆ 5 วินาที เพื่อทำการสุ่มเมนูอาหารที่เก็บไว้ในฐานข้อมูล โดยฐานข้อมูลที่ผมเลือกใช้เก็บข้อมูลก็คือ [Firebase](https://firebase.google.com/)

โดยในโปรเจคนี้ได้รับประสบการณ์ความรู้เกียวกับการเขียนโค้ดในรูปแบบใหม่ ได้ฝึกการใช้ฐานข้อมูลแบบ NoSQL แม้จะติดคัดบ้างในการใช้งานเพราะตอนนั้น [Firebase](https://firebase.google.com/) เป็นความรู้ใหม่สำหรับผม แต่เมื่อทำการศึกษาอย่างจริงจังก็รู้สึกว่าใช้ได้ง่ายเหมือนภาษา SQL ทั่วๆไป และ ทำให้ผมได้รู้ว่ามีบริการ Google API หลายตัวที่น่าสนใจ
