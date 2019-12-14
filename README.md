# Vote application by Somtum Framework

เรียนรู้การสร้างแอพพลิเคชั่นอย่างง่ายด้วย Somtum Framework และเทคนิคการรับมือกับการใช้งานในปริมาณมากๆ ด้วยเทคนิคบ้านๆ ที่ใครๆก็สามารถทำได้

## คุณสมบัติ

- ออกแบบโดยเน้นการรับโหลดสูงๆ เท่าที่จะทำได้สำหรับ PHP
- ไม่เน้นเทคนิคพิเศษ แต่เน้นให้ใช้ทรัพยากรที่มีอยู่อย่างคุ้มค่าและหาได้ง่าย ประหยัดต้นทุน
- จุดประสงค์การออกแบบ เน้นการใช้งานภายในองค์กร โดยมีเกณฑ์ความปลอดภัยในระดับพื้นฐาน เหมาะสมกับการใช้งานในระดับทั่วๆไป

## ความต้องการ

- PHP 5.3 ขึ้นไป
- PDO Mysql

## การติดตั้งและนำไปใช้งาน

1. อัปโหลดไฟล์ทั้งหมดขึ้นไปยัง Server ยกเว้น vote.sql
2. แก้ไขไฟล์ settings/config.php ให้ถูกต้อง
3. ปรับ chmod ให้ settings/config.php และ ไดเร็คทอรี่ datas/ รวมทั้งไฟล์ทั้งหมดในนั้น ให้สามารถเขียนได้
4. สร้างฐานข้อมูลจากไฟล์ vote.sql
5. เข้าระบบโดยใช้ username: admin@localhost และ password: admin

## เงื่อนไขการใช้งาน (License)

- สามารถนำไปใช้งานได้ ดัดแปลงได้ ไม่มีข้อจำกัด
- ห้ามขาย
- ไม่รับผิดชอบข้อผิดพลาดใดๆทั้งสิ้น

## เว็บไซต์หลัก

https://thestandard.co/personoftheyear2019/

## ตัวอย่าง

- Front End : https://thestandard.co/personoftheyear2019/ลลิษา มโมนบาล 
- Admin : https://Votes/thestandard.co/personoftheyear2019/admin.php
