## การทดลองที่ 5 เรื่อง การเขียนโปรแกรมเชื่อมต่อไวไฟและเว็บเซอร์เวอร์
# วัตถุประสงค์
1. เพื่อศึกษาการเขียนโปรแกรมเชื่อมต่อไวไฟและเว็บเซอร์เวอร์
# อุปกรณ์ที่ใช้
1. คอมพิวเตอร์
2. serial port
3. ไมโครคอนโทรลเลอร์ (ESP01)
4. สาย USB
# ศึกษาข้อมูลเบื้องต้น
https://www.youtube.com/watch?v=VX-QNQcO-b4
# วิธีการทำการทดลอง
1. ตั้งค่าโปรแกรมโดยทำการเชื่อมต่อwifi  

![image](https://user-images.githubusercontent.com/80881207/112422468-8ce48f80-8d63-11eb-9d01-31fbc5dec348.png)

2. เลือกตัวอย่างโปรแกรมที่ต้องการใช้ในที่นี้จะเลือกตัวอย่างที่ 5 พิมพ์ cd 05_Wifi-Web-Server ตามด้วย vi src/main.cpp
 
 ![image](https://user-images.githubusercontent.com/80881207/112422494-953cca80-8d63-11eb-8eac-024de4b336c4.png)

3. upload โปรแกรมในขณะที่อัพโหลดนำไมโครคอนโทรลเลอร์
4. ใช้คำสั่ง pio device monitor เพื่อดูผลลัพธ์ที่แสดงผลออกมาโดยผลลัพธ์ที่แสดงออกมานั้นจะเป็น ip address แล้วจึงนำ ip address ไปทดสอบที่ browser
 
 ![image](https://user-images.githubusercontent.com/80881207/112422518-9c63d880-8d63-11eb-9d85-cc4f7a0aef5a.png)

# การบันทึกผลการทดลอง
ผลลัพธ์ที่แสดงออกมานั้นจะเป็น Hello 1 แล้วนับไปเรื่อยๆ
# อภิปรายผลการทดลอง
สามารถนำ ip address ไปใส่ที่ browser เพื่อทดสอบโปรแกรมได้
# คำถามหลังการทดลอง
Q:นอกจาก password แล้วใช้อะไรเชื่อมต่อกับwifi
A:ssid
