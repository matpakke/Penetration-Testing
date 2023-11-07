# Penetration-Testing
https://play.mooc.ncsa.or.th/course/2

Course information
8 chapters
137 labs
144 questions
11 hours 35 minutes estimated time of completion

## Chapter 1 - Penetration Test
เรียนรู้เกี่ยวกับ Penetration Test
- [Asymmetric Encryption](https://play.mooc.ncsa.or.th/lab/34)
- [Penetration Test คืออะไร](https://play.mooc.ncsa.or.th/lab/35)
- [Pre-Engagement](https://play.mooc.ncsa.or.th/lab/36)
- [Information Gathering](https://play.mooc.ncsa.or.th/lab/37)
- [Github Hacking](https://play.mooc.ncsa.or.th/lab/38)

### Solution
1. เปิด lab ขึ้นมาจะพบว่ามี port 80 ขึ้นมา
2. เข้าใช้งานจะพบว่าเว็บไซต์นั้นเป็น sample website โดยสามารถติดต่อผู้พัฒนาได้ที่ @supervalentine
3. เข้า https://github.com จากนั้น search โดยใช้ keyword เป็น "supervalentine" credential แล้วเข้าไปดูในส่วนของ Code
4. Request ไปยังเว็บไซต์เป้าหมาย พร้อมกับระบุ parameter

```
username=sa
credential=JDM82XDVMcNI^wpdW7ZQ5
```
ตัวอย่าง request

http://<TARGET>/?username=sa&credential=JDM82XDVMcNI^wpdW7ZQ5


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

