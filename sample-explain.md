## ผม 6310680589 วันนี้จะมาอธิบายโปรแกรมฉบับเข้าใจง่าย จะง่ายแค่เชิญรับฟังรับชมได้เลยครับ เห้ย รับชมรับฟัง!
## การเขียนโปรแกรมเพื่อรันบน Microcontroller
ในการเขียนโปรแกรม เราจะใข้คำสั่งloop ในการเขียน คำสั่งให้เพิ่มค่าตัวแปรcnt โดยการนับcnt ไปเรื่อยๆ โดยจะมีการนับใหม่โดยการกดดreset
## การเขียนโปรแกรมค้นหาWifi'
ในโปรแกรมที่ 2 จะแบ่งออกเป็น 2ส่วน ส่วนที่1 ส่วนของ void setup และส่วนที่2 ส่วนของ void loop โดยส่วนแรกทั้งหมดนี้จะ setup wifi ให้พร้อมทำงาน และในส่วนที่2 จะสแกนค้นหาไวไฟที่อยู่รอบๆตัว
และมีการกดปุ่ม resetเพื่อเริ่มต้นโปรแกรมใหม่ ผลลัพธ์ที่ได้โปรแกรมจะแสดงไวไฟที่ได้รับออกมา
## การเขียนโปรแกรม Output สัญญาณ Digital
ในโปรแกรทนี้หลักๆจะมีการsetup
ใช้คำสั่ง cnt เมื่อเป็นเลขคู่จะส่งค่าเป็นoff = HIGH
ใช้คำสั่ง cnt เมื่อเป็นเลขคี่จะส่งค่าเป็นon = LOW
แสดงผลดีเลย์ใน 0.5 วินาที โดยที่จะloopใหม่ทุกๆ 0.5 วินาที 
## การเขียนโปรแกรม Input สัญญาณ Digital
ในโปรแกรมนี้หลักๆจะมีการsetup และวนลูป แล้วแสดงผลโดยแสดง1เป็นค่าLOWไฟจะ=ปิด แสดงค่าเป็น0เป็นHIGH ไฟจะON=เปิด
## การเขียนโปรแกรมเชื่อมต่อ WIFI และ Webserver
ในโปรแกรมนี้หลักๆจะมีการsetup เพื่อเชื่อมต่อกับเซิร์ฟเวอร์ และจะมีการที่ให้เซิร์ฟเวอร์ตั้งรับคำสั่งต่างๆและวนลูปไปเรื่อยๆ
## การเขียนโปรแกรมสร้างไวไฟแอดเซสพอยต์
ในโปรแกรมนี้หลักๆจะมีการsetup อันดับแรกต้องกำหนด ชื่อผู้ใข้และรหัสก่อน และ คอมพิวเตอร์จะเตรียมรับคำสั่งต่างๆและใช้คำสั่งloopไปเรื่อยๆ
