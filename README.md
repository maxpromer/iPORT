# iPORT

ปลั๊กอินเสริม เพิ่มบล็อกเกี่ยวกับบอร์ด IO และ Servo สำหรับบอร์ด KidBright32 V1.5 ในโปรแกรม KidBrightIDE

## การติดตั้ง

 1. ดาวน์โหลดไฟล์ปลั๊กอินจากส่วนล่างของหน้านี้ จะได้ไฟล์ iPORT_vx.x.x.zip
 2. เปิดโปรแกรม KidBrightIDE กด Plugins > Install Plugins
 3. เลือกไฟล์ปลั๊กอิน (iPORT_vx.x.x.zip) ที่ดาวน์โหลดไว้
 4. โปรแกรม KidBrightIDE จะปิดแล้วเปิดใหม่ บล็อกใหม่จะอยู่ในเมนู Plugin > iPORT

## การใช้งาน
 
ปลั๊กอินนี้ มีบล็อกให้เลือกใช้งานในเมนู iPORT ดังนี้

| บล็อกภาษาไทย | บล็อกภาษาอังกฤษ |
|--|--|
| ![](https://sv1.picz.in.th/images/2020/08/05/E185i0.png) | ![](https://sv1.picz.in.th/images/2020/08/05/E1HYY8.png) |

### บล็อกเขียนค่าดิจิทัล

| บล็อกภาษาไทย | บล็อกภาษาอังกฤษ |
|--|--|
| ![บล็อกเขียนค่าดิจิทัล](https://sv1.picz.in.th/images/2020/08/05/E18QH8.png) | ![digital write](https://sv1.picz.in.th/images/2020/08/05/E1H7Xz.png) |

ใช้เขียนค่าดิจิทัลไปที่ช่อง OUT1 OUT2 18 19 และ 23 โดยบล็อกจะรับค่าเป็นตัวเลขจำนวนเต็ม 0 หรือ 1

### บล็อกอ่านค่าดิจิทัล

| บล็อกภาษาไทย | บล็อกภาษาอังกฤษ |
|--|--|
| ![บล็อกอ่านค่าดิจิทัล](https://sv1.picz.in.th/images/2020/08/05/E18loP.png) | ![digital read](https://sv1.picz.in.th/images/2020/08/05/E1HzRR.png) |

ใช้อ่านค่าดิจิทัลจากช่อง IN1 IN2 IN3 IN4 18 19 และ 23 โดยบล็อกจะให้ค่าเป็นตัวเลข 0 หรือ 1

### บล็อกอ่านค่าแอนะล็อก

| บล็อกภาษาไทย | บล็อกภาษาอังกฤษ |
|--|--|
| ![บล็อกอ่านค่าแอนะล็อก](https://sv1.picz.in.th/images/2020/08/05/E18oJt.png) | ![analog read](https://sv1.picz.in.th/images/2020/08/05/E1H460.png) |

ใช้อ่านค่าแอนะล็อกจากช่อง IN1 IN2 IN3 IN4 โดยบล็อกจะให้ค่าเป็นตัวเลข 0 ถึง 4095 (12 บิต)

### บล็อกเขียนค่าแอนะล็อก

| บล็อกภาษาไทย | บล็อกภาษาอังกฤษ |
|--|--|
| ![บล็อกเขียนค่าแอนะล็อก](https://sv1.picz.in.th/images/2020/08/05/E18P5l.png) | ![analog write](https://sv1.picz.in.th/images/2020/08/05/E1HNMu.png) |

ใช้สร้างสัญญาณ PWM ที่ช่อง OUT1 OUT2 18 19 และ 23 โดยบล็อกจะรับค่าเป็นตัวเลขจำนวนเต็ม 0 ถึง 1023

### บล็อกควบคุมเซอร์โวมอเตอร์

| บล็อกภาษาไทย | บล็อกภาษาอังกฤษ |
|--|--|
| ![บล็อกควบคุมเซอร์โวมอเตอร์](https://sv1.picz.in.th/images/2020/08/05/E18sVk.png) | ![servo](https://sv1.picz.in.th/images/2020/08/05/E1Hf1Z.png) |

ใช้ควบคุมองศาการหมุนของเซอร์โวมอเตอร์ที่ช่อง SERVO1 SERVO2 OUT1 และ OUT2 บล็อกจะรับค่าเป็นตัวเลขจำนวนเต็ม 0 ถึง 179 (หน่วยองศา)
