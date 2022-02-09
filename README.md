# นางสาวศศิกานต์ ทองบ่อ 6310610065

## Markdown
สามารถกำหนดขนาดของหัวข้อได้โดยใช้จำนวนของ # ในการกำหนด

สามารถเน้นข้อความด้วยตัวหนา ตัวเอียง ได้จากการใช้สัญลักษณ์และแป้นพิมพ์ลัด โดยตัวหนาทำได้โดยใช้สัญลักษณ์ **หรือกด Ctrl+ B ตัวเอียงทำได้โดยใช้สัญลักษณ์ * หรือกด Ctrl+ I

สามารถอ้างข้อความด้วยเครื่องหมาย > หรือกด Ctrl+ E

สามารถแสดงรูปภาพโดยเพิ่ม ! และตัดข้อความแสดง [] แทน ในจากนั้นใส่ลิงค์ของรูปภาพใน ()วงเล็บ

สามารถพิมพ์ : เพื่อเพิ่มอิโมจิ โดยเมื่อพิมพ์ : จะแสดงรายการอีโมจิที่แนะนำ เมื่อคุณพบอีโมจิที่ต้องการแล้ว ให้กดTabหรือEnterเพื่อให้ผลลัพธ์
## สรุป ESP-01 microcontroller
Digital คือ การเอาสัญญาณไฟฟ้ามาแทนด้วยตัวเลขซึ่งเป็นตัวเลขฐานสอง มีแค่ 0 และ 1 ใช้แทนการทำงานของสัญญาณขึ้นอยู่กับแรงดันต่างๆ ว่าเป็น on หรือ off

Voltage คือ ความต่างศักย์ไฟฟ้าระหว่างจุด 2 จุดมีหน่วยเป็นโวลต์ แบ่งเป็น 2 ประเภท ได้แก่ ไฟฟ้ากระแสสลับ เช่น ไฟบ้าน และไฟฟ้ากระแสตรง เช่น แบตเตอรี่

Computer ใช้ประโยชน์ในการคำนวณหรือการทำงานอื่นๆอย่างหลากหลายและอย่างรวดเร็ว

Internet ใช้ในการเชื่อมโยงอุปกรณ์ต่างๆเข้าด้วยกัน

program lang ภาษาที่ใช้เขียนในโปรแกรมเพื่อให้คอมพิวเตอร์ทำงานตามคำสั่งที่เขียนลงไป

platformio คือ การพัฒนาซอฟแวร์แบบเปิด ใช้วิธีการเขียนโปรแกรมแบบเดียวแต่สามารถเขียนลงบน microcontroller ได้หลายแบบ

## สรุปการทดลอง ESP-01 จำนวน 6 การทดลอง

### Run example 1
การเขียนโปรแกรมลงใน microcontroller ด้วย platformio แบ่งเป็นสองส่วน ได้แก่ setup และ loop โดยให้มีความหน่วงเวลา 1 วินาที เมื่อ upload เข้าไป เพื่อให้ รับโปรแกรมใหม่เข้าไปจะต้องกดปุ่มในตัว microcontroller เมื่อ upload เข้าไปเสร็จจะใช้คำสั่ง pio device monitor จะเห็นว่าตัวแปร count ที่เริ่มจาก 0 จะถูกนับทีละ 1 จะแสดงผลในทุกๆ 1 วินาที 

### Run example 2
โปรแกรมค้นหา wifi จะมีสองส่วน ได้แก่ setup หรือ set wifi และ loop เมื่อ upload เข้าไปเสร็จแล้วจะแสดงผลการค้นหา wifi ออกมา

### Run example 3
microcontroller จะมี output port และ input port โดยจะเสียบไปที่ USB  ที่มี adapter เป็นตัวเชื่อม ในการทดลองจะ set ให้ port 0 เป็น output เมื่อ upload เสร็จแล้วจะแสดงผลเลขคี่เป็น on และเลขคู่เป็น off จะแสดงผลวนลูป ทุกๆ 0.5 วินาที

### Run relay
เอา microcontroller ไปเสียบที่ relay เพื่อควบคุมการเปิดปิดสวิตซ์ของอุปกรณ์

### run example 4
นำสัญญาณ input จากภายนอกเข้ามาใน microcontroller แบ่งเป็นสองส่วน ได้แก่ ส่วน setup จะให้ port 0 เป็น  input และ port 2 เป็น output เมื่ออัพโหลดเสร็จโปรแกรมจะอ่านข้อมูลจาก port 0 ถ้า input เป็น 1 จะติดไฟที่ port 2 แต่ถ้า input เป็น 0 จะไม่ติดไฟ

### Run wifi
โปรแกรมสร้าง web surver ผ่าน wifi ให้ใส่ชื่อ wifi และ password ลงไปในโปรแกรมเมื่อ upload เข้าไปแล้วจะทำให้สามารถเชื่อม wifi ที่เราต้องการได้

### Run wifi AP
เป็นการปล่อย wifi จากตนเองให้คนอื่นเข้ามาเชื่อมต่อได้ โดยต้องกำหนด IP address จากนั้นเตรียม webserver แล้วกำหนด IP , ssid และ password ลงไป เมื่อ upload เสร็จแล้วจะทำให้อุปรกรณ์เครื่องอื่นเชื่อมต่อ wifi ที่เราปล่อยออกมาได้


