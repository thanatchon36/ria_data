Fingerprint Irls Characteristic
Facial Volce
Identification &
Verification
Result
Biometric Capture
X
Decision
Biometric
Sample
Matching
Score
Signal processing
||||
Comparison
Data storage
metric
Template
Trans
Transfer
(1) การรวบรวมข้อมูลชีวมิติ (Capture) เป็นขั้นตอนการรวบรวมอัตลักษณ์ของบุคคลด้วย
อุปกรณ์รับข้อมูล (Sensor) ต่าง ๆ และแปลงให้อยู่ในรูปแบบข้อมูลอิเล็กทรอนิกส์ เพื่อให้ได้มาซึ่งข้อมูลชีวมิติ
ตั้งต้น เช่น การรวบรวมภาพใบหน้าด้วยกล้อง การรวบรวมภาพลายนิ้วมือด้วยอุปกรณ์อ่านลายนิ้วมือ
(2) การประมวลอัตลักษณ์ (Signal processing) เป็นขั้นตอนการประมวลข้อมูลชีวมิติตั้งต้น
ให้เป็นเทมเพลตชีวมิติ ด้วยวิธีการทางอิเล็กทรอนิกส์ทำให้ไม่สามารถแปลงเทมเพลตชีวมิติให้กลับเป็นข้อมูลชีวมิติ
ตั้งต้นได้ เช่น การประมวลผลภาพใบหน้าจากระยะห่างระหว่างจุดสังเกตสำคัญจำนวนมาก เช่น ดวงตา หางคิ้ว
ความกว้างริมฝีปาก จุดสังเกตบนลายนิ้วมือ (Minutiae)
(3) การเก็บข้อมูล (Data storage) เป็นขั้นตอนการจัดเก็บข้อมูลอ้างอิงชีวมิติไว้ในระบบจัดเก็บ
ข้อมูล ซึ่งมีการเชื่อมโยงข้อมูลอ้างอิงชีวมิติกับข้อมูลส่วนบุคคลอื่นของผู้ใช้บริการทางการเงิน (เช่น ชื่อ-นามสกุล
เลขประจำตัวประชาชน ที่อยู่) เพื่อใช้ในการเปรียบเทียบอัตลักษณ์ของบุคคลนั้น
(4) การเปรียบเทียบอัตลักษณ์ (Comparison) เป็นขั้นตอนการเปรียบเทียบระหว่างข้อมูลชีวมิติ
ที่ต้องการระบุ พิสูจน์ หรือยืนยันตัวตนผู้ใช้บริการ กับข้อมูลอ้างอิงชีวมิติที่เก็บไว้ในระบบจัดเก็บข้อมูลภายใน
องค์กรหรือแหล่งข้อมูลที่เชื่อถือได้ โดยแสดงผลการเปรียบเทียบเป็นระดับความเชื่อมั่นการเป็นบุคคลเดียวกัน
ซึ่งมีการใช้งานหลักใน 2 ลักษณะ ได้แก่
เปรียบเทียบอัตลักษณ์ของบุคคล เพื่อตัดสินใจว่าเป็นบุคคลนั้นจริงหรือไม่
• การระบุตัวตน (Identification) คือ การนำข้อมูลชีวมิติของบุคคลมาเปรียบเทียบตัวบุคคล
กับข้อมูลอ้างอิงชีวมิติที่บุคคลนั้นได้ลงทะเบียนไว้ และบันทึกอยู่ในระบบจัดเก็บแล้ว เพื่อระบุว่าเป็นบุคคลที่มี
ข้อมูลอยู่ในระบบจัดเก็บข้อมูลหรือไม่ เช่น การใช้ภาพใบหน้าหรือลายนิ้วมือ เพื่อค้นหาหรือระบุตัวตนของ
บุคคลหนึ่งที่มีข้อมูลอ้างอิงชีวมิติบันทึกไว้ในระบบจัดเก็บข้อมูลแล้ว
• การพิสูจน์ตัวตนและยืนยันตัวตน (Verification and authentication) คือ การนำข้อมูล
ชีวมิติของบุคคลมาเปรียบเทียบตัวบุคคลกับแหล่งข้อมูลที่เชื่อถือได้ เพื่อพิสูจน์และยืนยันว่าเป็นบุคคลนั้นจริง
ตามที่อ้างถึงหรือไม่ เช่น กระบวนการรู้จักผู้ใช้บริการในการเปิดบัญชีเงินฝากด้วยการเปรียบเทียบข้อมูลชีวมิติ
ที่ได้จากการถ่ายภาพบุคคลกับข้อมูลที่บันทึกในบัตรประจำตัวประชาชน
(5) การตัดสินใจ (Decision) เป็นขั้นตอนแสดงผลลัพธ์จากการเปรียบเทียบอัตลักษณ์ของ
บุคคล โดยเปรียบเทียบค่าคะแนนความเชื่อมั่นที่ยอมรับได้ (Threshold) กับค่าคะแนนความเชื่อมั่นจากการ
