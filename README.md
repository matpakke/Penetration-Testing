# Penetration-Testing
https://play.mooc.ncsa.or.th/course/2

## Course information
- 8 chapters
- 137 labs
- 144 questions
- 11 hours 35 minutes estimated time of completion

## Chapter 1 - Penetration Test
เรียนรู้เกี่ยวกับ Penetration Test
- [Asymmetric Encryption](https://play.mooc.ncsa.or.th/lab/34)
- [Penetration Test คืออะไร](https://play.mooc.ncsa.or.th/lab/35)
- [Pre-Engagement](https://play.mooc.ncsa.or.th/lab/36)
- [Information Gathering](https://play.mooc.ncsa.or.th/lab/37)
- [Github Hacking](https://play.mooc.ncsa.or.th/lab/38)
## Question
ให้ใช้วิธีการ OSINT เพื่อค้นหาข้อมูล source code ของเครื่องเป้าหมาย โดยค้นหาข้อมูลใน Github โดยใช้ keyword “supervalentine” credential
## Solution
1. เปิด lab ขึ้นมาจะพบว่ามี port 80 ขึ้นมา
2. เข้าใช้งานจะพบว่าเว็บไซต์นั้นเป็น sample website โดยสามารถติดต่อผู้พัฒนาได้ที่ @supervalentine
3. เข้า https://github.com จากนั้น search โดยใช้ keyword เป็น "supervalentine" credential แล้วเข้าไปดูในส่วนของ Code
4. Request ไปยังเว็บไซต์เป้าหมาย พร้อมกับระบุ parameter

```
username=sa
credential=JDM82XDVMcNI^wpdW7ZQ5
```
ตัวอย่าง request
```
http://<TARGET>/?username=sa&credential=JDM82XDVMcNI^wpdW7ZQ5
```
- [Metadata ของรูปภาพ](https://play.mooc.ncsa.or.th/lab/39)Question
## Question
ให้ download รูปภาพจาก link ด้านล่าง จากนั้นทำการค้นหา key ของผู้สร้างภาพดังกล่าว โดยลักษณะการตอบคือ osint{<KEY>} เช่น osint{1234567890} เป็นต้น
[https://drive.google.com/open?id=1Uxq2zilkf16Bq1A0SSxtH-spYSYcriQa](https://drive.google.com/open?id=1Uxq2zilkf16Bq1A0SSxtH-spYSYcriQa)
## Solution
1. ตรวจสอบ metadata ของ file โดยใช้คำสั่ง
```
exiftool heart.jpg
```
จะพบว่า creator คือ supervalentine

2. ค้นหาข้อมูลใน Twitter.com ในหน้า https://twitter.com/search-home ด้วยคำว่า supervalentine ‘la la la’ 
3. ค้นพบ account twitter ของผู้สร้างภาพ
4. ตรวจสอบ twitter ของผู้สร้างภาพจะพบว่ามีการเขียน key ไว้ใน post แรก ๆ ของ twitter

คำตอบคือ osint{667Y7hb$x}
  
## Chapter 2 - Scanning
เรียนรู้เกี่ยวกับ Scanning แบบต่าง ๆ


## Chapter 3 - Linux Knowledge
เรียนรู้เกี่ยวกับการใช้งาน Linux


## Chapter 4 - Netcat
เรียนรู้การใช้งาน Netcat


## Chapter 5 - Network Security
เรียนรู้เกี่ยวกับ network security


## Chapter 6 - Web Security
เรียนรู้เกี่ยวกับ web application security


## Chapter 7 - Post Explotiation
เรียนรู้เกี่ยวกับการโจมตีหลัง Exploit สำเร็จ


## Chapter 8 - Reporting
เรียนรู้เกี่ยวกับการเขียน Penetration test report

