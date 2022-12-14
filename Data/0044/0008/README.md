4.2 ประเด็นสำคัญที่ควรคำนึงถึงในการป้องกันความเสี่ยงที่เกี่ยวข้องกับการใช้เทคโนโลยีชีวมิติ
เทคโนโลยีชีวมิติเกี่ยวข้องกับการใช้ข้อมูลชีวมิติของบุคคลในการระบุ พิสูจน์ หรือยืนยันตัวตน ซึ่งเป็น
ข้อมูลส่วนบุคคลที่มีความสำคัญ จึงจำเป็นต้องมีการควบคุมดูแลในทุกขั้นตอนการทำงานที่เกี่ยวข้องอย่างรัดกุม
ปลอดภัย โดยมีประเด็นสำคัญที่ควรพิจารณาและระมัดระวัง เพื่อป้องกันความเสี่ยงในการใช้เทคโนโลยีชีวมิติ
สรุปตามแผนภาพ และคำอธิบายได้ ดังนี้
น
ขนตอน
สำคัญ
ประเด็นสำคัญ
ควรระวัง
1. Capture
เก็บอัตลักษณ์ทางกายภาพ
ของผู้ใช้ด้วยอุปกรณ์ต่าง ๆ
การควบคุม
ความเสี่ยง
Spoofing:
การปลอมลายนิ้วมือ
ปลอมภาพใบหน้า
การเก็บข้อมูลที่มีคุณภาพ
ตรวจสอบการปลอมแปลง
ความปลอดภัยของอุปกรณ์
ช่องทางรับส่งข้อมูลชีวมิติ
การสอบทานคุณภาพข้อมูล
|
2. Signal processing
แปลงอัตลักษณ์ให้เป็น
ข้อมูลเทมเพลตชีวมิติ
(Biometric Template)
ที่พึงปฏิบัติ ดังนี้
Man-in-the-middle:
การดักจับ การปลอมแปลง
ข้อมูลชีวมิติ
e
3. Data storage
จัดเก็บข้อมูลอ้างอิงชีวมิติ
ไว้ในระบบจัดเก็บข้อมูล
Compromise:
การลักลอบเข้าถึงข้อมูล
ข้อมูลรั่วไหล หรือสูญหาย
4. Comparison
เปรียบเทียบอัตลักษณ์กับ
ข้อมูลอ้างอิงชีวมิติ
การรักษาความปลอดภัยระบบ IT
- เข้ารหัสข้อมูลชีวมิติ
แยกข้อมูลชีวมิติออกจากข้อมูลอื่น
- ควบคุมการเข้าถึงข้อมูลชีวมิติ
การจัดเก็บ log การเข้าถึง เปลี่ยนแปลงข้อมูล
การพัฒนา/คัดเลือกแบบจำลองที่เหมาะสม เชื่อถือได้
ทบทวนอย่างสม่ำเสมอ
ปรับปรุงข้อมูลชีวมิติให้เป็นปัจจุบัน
กระบวนการป้องกันการ Override การตัดสินใจ
กระบวนการรองรับกรณีไม่ผ่านการพิสูจน์ตัวตน
นโยบายการกำกับดูแลข้อมูลชีวมิติ การป้องกันความเสี่ยงด้านไซเบอร์ การคุ้มครองผู้บริโภค การกำกับดูแลผู้ให้บริการภายนอก
(1) การปลอมแปลงอัตลักษณ์ (Spoofing) คือ การสร้างหรือปรับแต่งลักษณะทางกายภาพและ
ลักษณะทางพฤติกรรม เพื่อเลียนแบบอัตลักษณ์ของบุคคลอื่นด้วยวิธีต่าง ๆ เช่น การใช้วัสดุเทียมเพื่อเลียนแบบ
ลายนิ้วมือ การใช้หน้ากากเพื่อหลอกอุปกรณ์รับข้อมูล และการใช้ภาพถ่ายหรือภาพเคลื่อนไหวที่บันทึกไว้
แทนการถ่ายภาพหรือการเคลื่อนไหวจริงของบุคคล
(2) การดักจับข้อมูล (Man-in-the-middle) คือ การลักลอบคัดลอกหรือแก้ไขข้อมูลชีวมิติที่อยู่
ระหว่างขั้นตอนการรับส่งข้อมูลระหว่างกันภายในระบบ เช่น การติดตั้งอุปกรณ์ดักจับข้อมูลชีวมิติในโครงข่าย
(3)การลักลอบเข้าถึงข้อมูล (Compromise) คือ การพยายามลักลอบเจาะระบบจัดเก็บข้อมูล
อ้างอิงชีวมิติ เพื่อคัดลอก แก้ไข หรือทําลายข้อมูลอ้างอิงชีวมิติ
(4) การตัดสินผิดพลาด (Inaccuracy) คือ การที่ระบบระบุ พิสูจน์ หรือยืนยันตัวตนบุคคล
ผิดพลาดจากระดับที่กําหนด โดยอาจเกิดจากกระบวนการเปรียบเทียบอัตลักษณ์ที่ไม่แม่นยำหรือ
กระบวนการเรียนรู้ของระบบ (Model training) ยังไม่เพียงพอ
(5) การแทรกแซงการทำงานของระบบ (Override) คือ การพยายามแก้ไขหรือข้ามขั้นตอน
การตัดสินใจของระบบการเปรียบเทียบอัตลักษณ์ เช่น การแก้ไขค่าคะแนนความเชื่อมั่นที่ยอมรับได้ให้อยู่
ในระดับต่ำลง (Threshold manipulation) การปรับเปลี่ยนกระบวนการตัดสินใจโดยข้ามหรือแทรกแซง
ขั้นตอนประมวลผลของระบบจริง
Inaccuracy:
ไม่แม่นยำ ตัดสินผิดพลาด
5. Decision
แสดงผลลัพธ์ว่าเป็น
ตัวบุคคลนั้นจริงหรือไม่
Override:
การแทรกแซง หรือข้าม
ขั้นตอนการพิสูจน์ตัวตน
5. หลักการที่พึงปฏิบัติสำหรับผู้ให้บริการทางการเงิน
หลักการพึงปฏิบัติที่สำคัญในการใช้เทคโนโลยีชีวมิติในการให้บริการทางการเงินมี 6 ข้อ ซึ่งผู้ให้บริการ
ทางการเงินต้องถือปฏิบัติเป็นมาตรฐานขั้นต่ำในการให้บริการทางการเงิน โดยมีผลลัพธ์ที่คาดหวังและแนวทาง
