
# วิธีการติดตั้ง platformio

1.ติดตั้ง git โดยคลิกเข้าไปที่ลิงค์ https://git-scm.com/download/win แล้วเลือกกดดาวโหลด 64-bit Git for Windows Setup. แล้วทำการติดตั้งให้สำเร็จ

2.ติดตั้ง nodejs โดยคลิกเข้าไปที่ลิงค์ https://nodejs.org/en/download/ กดเลือก Windows Installer (.msi) 64bit แล้วทำการติดตั้งให้สำเร็จ

3.ติดตั้ง python โดยคลิกเข้าไปที่ลิงค์ https://www.python.org/downloads/windows/ กดเลือก Download Windows installer (64-bit) ถัดมาให้กดคลิกไฟล์เพื่อติดตั้งแล้วคลิกถูกเพิ่มที่ Add Phython 3.9 To PATH แล้วทำการติดตั้งให้สำเร็จ 

4.เปิด command prompt หรือ cmd รันคำสั่ง git clone https://github.com/choompol-boonmee/iotset1.git 

5.รัน pip install -U platformio บน command prompt หรือ cmd

6.เพื่อเข้าไปโฟลเดอร์ iotset1 รัน cd iotset1/examples และ dir ตามลำดับ

7.เพื่อตรวจสอบดูโฟลเดอร์ตัวอย่าง ex01,ex02,ex03 ตัวอย่างโดยรัน cd iotset1/examples/ex01 และ pio run ตามลำดับ
