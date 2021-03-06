## การทดลองที่ 7 เรื่อง การเขียนโปรแกมเซนเซอร์เพื่อใช้ในการรดน้ำต้นไม้
# วัตถุประสงค์
1. เพื่อประยุกต์ใช้ความรู้เกี่ยวกับไมโครคอนโทรลเลอร์
2. เพื่อศึกษาเกี่ยวกับไมโครคอนโทรเลอร์
3. เพื่อประโยชน์ทางการเกษตร
# อุปกรณ์ที่ใช้
1. สาย USB
2. คอมพิวเตอร์
3. serial port
4. ไมโครคอนโทรลเลอร์ (arduino)
5. sensor แสง
6. adapter
# ศึกษาข้อมูลเบื้องต้น
1. https://youtu.be/NLIUsWLEpmg
2. https://dspace.rmutk.ac.th/bitstream/handle/123456789/2510/143%20%E0%B8%A3%E0%B8%B0%E0%B8%9A%E0%B8%9A%E0%B8%A3%E0%B8%94%E0%B8%99%E0%B9%89%E0%B8%B3%E0%B9%81%E0%B8%9B%E0%B8%A5%E0%B8%87%E0%B8%9C%E0%B8%B1%E0%B8%81%E0%B8%AD%E0%B8%B1%E0%B8%95%E0%B9%82%E0%B8%99%E0%B8%A1%E0%B8%B1%E0%B8%95%E0%B8%B4.pdf?sequence=1&isAllowed=y
# วิธีการทำการทดลอง
1. นำไมโครคอนโทรลเลอร์ต่อกับ serial port โดยผ่าน adapter

![image](https://user-images.githubusercontent.com/80881207/112422318-44c56d00-8d63-11eb-90fb-11d682444c21.png)

2. เลือกตัวอย่างโปรแกรมที่ต้องการใช้ในที่นี้จะเลือกตัวอย่างที่ 4 พิมพ์ cd 04_Input-port ตามด้วย vi src/main.cpp

![image](https://user-images.githubusercontent.com/80881207/112422324-4a22b780-8d63-11eb-9ae1-c58fc1533614.png)
 
3. รันโปรแกรม
4. นำ sensor แสงมาต่อ
 
 ![image](https://user-images.githubusercontent.com/80881207/112422345-50b12f00-8d63-11eb-852c-90434d5bf849.png)
 
 5. ติดตั้งกับที่รดน้ำหาก read ได้ 0 ไฟจะติดและตั้งค่าให้น้ำออกมา ถ้าได้ 1 ไฟไม่ติดและไม่มีน้ำไหลออกมา

# การบันทึกผลการทดลอง
เมื่อ read ได้ 0 ไฟจะติดและจะดำเนินการรดน้ำต้นไม้ แต่เมื่อไฟไม่ติดหรือ read ได้ 1 จะไม่ทำการรดน้ำต้นไม้
# อภิปรายผลการทดลอง
การทดลองครั้งนี้ไม่ได้ทำการทดลองแบบจริงๆ จึงไม่สามารถระบุได้ว่าจะประสบผลสำเร็จหรือไม่ แต่มีความเป็นไปได้
# คำถามหลังการทดลอง
Q : การทดลองครั้งนี้มีประโยชน์ต่อด้านใดมากที่สุด 
A : ด้านการเกษตร 



