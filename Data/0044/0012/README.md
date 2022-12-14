ได้ต่อเนื่องเพื่อป้องกันการทดลองทําซ้ำ กำหนดระยะเวลาที่ระบบยอมให้ทำธุรกรรมด้วยข้อมูลชีวมิติโดย
ผู้ใช้บริการต้องยืนยันตัวตนใหม่หากไม่มีกิจกรรมใด ๆ เกิดขึ้น (Time-out policy)
(4) กําหนดกระบวนการรองรับกรณีที่ระบบการเปรียบเทียบอัตลักษณ์ไม่สามารถใช้งานได้ หรือกรณี
ที่ผู้ใช้บริการตัวจริงพิสูจน์หรือยืนยันตัวตนไม่สำเร็จ (False reject) โดยควรมีกระบวนการรองรับที่เหมาะสม
กับรูปแบบการให้บริการ รวมทั้งลักษณะและความเสี่ยงของธุรกรรม เช่น การมีทางเลือกให้ผู้ใช้บริการพิสูจน์
หรือยืนยันตัวตนด้วยวิธีอื่น หรือการแสดงหลักฐานอื่นเพิ่มเติมประกอบการพิสูจน์ หรือยืนยันตัวตน
(5) กำหนดแนวทางการดูแลรักษาความปลอดภัยของข้อมูลในขั้นตอนการประมวลอัตลักษณ์และ
ขั้นตอนเปรียบเทียบอัตลักษณ์ โดยเฉพาะกรณีที่ผู้ให้บริการทางการเงินมีการใช้บริการประมวลอัตลักษณ์หรือ
เปรียบเทียบอัตลักษณ์ผ่านระบบของผู้ให้บริการภายนอก จะต้องไม่มีการเก็บหรือคงค้างข้อมูลชีวมิติในระบบ
ของผู้ให้บริการภายนอก
หลักการที่ 4 การรักษาความปลอดภัยข้อมูลที่เกี่ยวข้องกับข้อมูลชีวมิติของผู้ใช้บริการ
ผลลัพธ์ที่คาดหวัง : ผู้ให้บริการทางการเงินมีการดูแลรักษาข้อมูลส่วนบุคคลที่เกี่ยวข้องกับข้อมูลชีวมิติ
ของผู้ใช้บริการที่เข้มงวดและรัดกุมตามมาตรฐานสากล เพื่อให้มั่นใจว่าข้อมูลของผู้ใช้บริการได้รับการปกป้อง
ดูแลอย่างปลอดภัย
แนวทางที่พึงปฏิบัติ
(1) กำหนดนโยบายและออกแบบระบบโครงสร้างพื้นฐานด้านเทคโนโลยีสารสนเทศ (IT infrastructure)
ที่คำนึงถึงความปลอดภัยของข้อมูลชีวมิติและความสามารถในการขยายขนาดเพื่อรองรับปริมาณธุรกรรมที่
เพิ่มขึ้นในอนาคต
(2) ไม่เก็บข้อมูลชีวมิติตั้งต้นของผู้ใช้บริการ โดยให้จัดเก็บเป็นเทมเพลตชีวมิติเพื่อใช้ในการ
เปรียบเทียบอัตลักษณ์ และต้องไม่สามารถแปลงย้อนกลับเป็นข้อมูลชีวมิติตั้งต้นได้ ยกเว้นกรณีภาพถ่ายใบหน้า
ของลูกค้า หรือกรณีที่ผู้ให้บริการทางการเงินมีความจำเป็นในการจัดเก็บข้อมูลชีวมิติตั้งต้นเพื่อปฏิบัติตามกฎหมาย
นอกจากนี้ ให้ปฏิบัติตามกฎหมายที่เกี่ยวข้องด้วย เช่น กฎหมายว่าด้วยการคุ้มครองข้อมูลส่วนบุคคล
(3) กำหนดกระบวนการจัดเก็บ รับส่ง และเชื่อมโยงข้อมูลอ้างอิงชีวมิติ ที่มีความรัดกุมปลอดภัย ได้แก่
(3.1) จัดเก็บและรับส่งข้อมูลอ้างอิงชีวมิติเพื่อให้ไม่สามารถระบุตัวตนเจ้าของข้อมูล และ
ไม่สามารถนำไปใช้ต่อได้โดยไม่ได้รับอนุญาต เช่น การเข้ารหัสข้อมูลอ้างอิงชีวมิติสำหรับการรับส่งข้อมูล
(Data-in-transit) ระหว่างขั้นตอนต่าง ๆ ตั้งแต่อุปกรณ์รับข้อมูล สายสื่อสาร จนถึงการบันทึกข้อมูลอ้างอิงชีวมิติ
(Data-at-rest) มีการเข้ารหัสในระดับฟิลด์ของระบบจัดเก็บข้อมูลหรือระดับไฟล์ ด้วยมาตรฐานการเข้ารหัส
ข้อมูลที่มีความมั่นคงปลอดภัยสอดคล้องกับมาตรฐานสากลที่ยอมรับโดยทั่วไป เช่น อัลกอริธึมการเข้ารหัส
(Encryption algorithm) และขนาดความยาวของกุญแจเข้ารหัสข้อมูล เป็นต้น รวมถึงมีกระบวนการเก็บรักษา
กุญแจเข้ารหัสที่มีความรัดกุม
- สามารถอ้างอิงการกำหนดจำนวนครั้งและระยะเวลาตามมาตรฐาน NIST SP 800-63B Digital Identity Guidelines Authentication and
Lifecycle Management และ ข้อเสนอแนะมาตรฐานฯ ว่าด้วยแนวทางการใช้ดิจิทัลไอดีสำหรับประเทศไทย - การยืนยันตัวตน ของสำนักงาน
พัฒนาธุรกรรมทางอิเล็กทรอนิกส์ ซึ่งจำกัดจำนวนครั้งของการยืนยันตัวตนด้วยชีวมิติให้ผิดพลาดอย่างต่อเนื่องได้ไม่เกิน 5 ครั้งกรณีทั่วไป หรือไม่เกิน
10 ครั้ง กรณีที่ใช้งานการตรวจจับการปลอมแปลงชีวมิติ โดยหากครบกำหนดแล้วต้องดำเนินการอย่างใดอย่างหนึ่ง ดังนี้
หน่วงเวลาอย่างน้อย 30 วินาทีก่อนอนุญาตให้ยืนยันตัวตนครั้งถัดไป และเพิ่มการหน่วงเวลาก่อนอนุญาตให้ยืนยันตัวตนครั้งต่อไปแบบ
Exponential เช่น หน่วงเวลาอย่างน้อย 30 วินาที 1 นาที 2 นาที 4 นาที 8 นาที และเ
และเพิ่มขึ้นตามจำนวนครั้งของการยืนยันตัวตนผิดพลาด
ระงับการยืนยันตัวตนด้วยชีวมิติและให้ผู้ใช้บริการยืนยันตัวตนด้วยวิธีอื่น
