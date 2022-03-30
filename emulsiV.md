# EmusiV

## วิธีการเปิดโปรแกรม

1. เข้าไปที่เว็บไซต์ riscv.org ตามภาพข้างล่างนี้

![รูปภาพ1](https://user-images.githubusercontent.com/98943603/160855793-bc91967b-1529-42fe-84be-5466c375f301.png)

2. คลิกไปที่ RISC-V Exchange >> Available Software ตามภาพด้านล่างนี้ 

![รูปภาพ2](https://user-images.githubusercontent.com/98943603/160855900-335251d7-0ef0-4e1b-8b87-a86d055f24f0.png)

3. เลื่อนลงหาช่อง EmusiV กดเลือก Working Instance ตาภาพข้างล่างนี้

![รูปภาพ3](https://user-images.githubusercontent.com/98943603/160855918-56aef67a-4a68-4a33-88ed-2e5a66dd3337.png)

4. เมื่อคลิกแล้วจะได้หน้าจอไมโครคอนโทรลเลอร์ดังภาพ

![รูปภาพ5](https://user-images.githubusercontent.com/98943603/160856395-283d4613-b72e-4787-8b17-46d16611c762.png)

## อธิบายหน้าจอไมโครคอนโทรลเลอร์

![รูปภาพ6](https://user-images.githubusercontent.com/98943603/160857048-4ac40db0-7d78-4951-8e57-ed8c8bb9f494.png)


ตามภาพอธิบายได้ดังนี้

1. Memory มีหน่วยความจำเป็นจำนวนมาก

2. General-purpose register หน่วยความจำขนาดเล็กมีแค่ 32 ตัว

3. Text I/O เป็น input/output ใช้สำหรับตัวอักษร

4. General-purpose I/O เป็น input/output ใช้สำหรับเซนเซอร์แสง

5. Bitmap output ใช่เขียนรูปจาก Memory

# การทำงานของ EmusiV

เราจะทำให้ output แสดงผลออกมาเป็นตัวย่อของชื่อและนามสกุล ของดิฉันชื่แ Sasikan Thongbor ดังนั้นจะให้แสดงออกมาเป็น ST

1. โดยใน address ที่ 20 จะเอาไว้กำหนดค่าที่ต้องการโดยค่า ช่องแรกตัว S จะใส่เป็นเลข 53 และช่องที่สองตัว T จะใส่เป็นเลข 54 จะได้ตาภาพข้างล่างนี้

![รูปภาพ8](https://user-images.githubusercontent.com/98943603/160861728-0eae83dc-3532-40c0-84d7-bb48d7c8be06.png)

ซึ่งเราสามารถทราบตัวเลขที่จะใส่ค่าได้จากตาราง ASCII 

![รูปภาพ9](https://user-images.githubusercontent.com/98943603/160862114-4b75c0d6-fab8-42c0-9dc1-e1e0f3fe95a5.png)




