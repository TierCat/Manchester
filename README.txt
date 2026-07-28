V5 PREMIUM FLOW
Flow ใหม่: Mystery unlock → tunnel countdown → Manchester United reveal → player reveal → Birthday reveal → 4 memories → letter → blow candles → penalty wish → final → real 9:16 story PNG export.
เปลี่ยนชื่อ: script.js > const CONFIG={name:"YOUR MVP"}
เปลี่ยนรูป: photo1.jpg ถึง photo4.jpg
Story export สร้างไฟล์ PNG 1080x1920 จริงด้วย Canvas โดยไม่ใช้ library ภายนอก

V6
- ใช้ Manchester United crest SVG ไฟล์ใหม่ที่ส่งมา
- รองรับเพลงชื่อ เพลงบอล.mp3
- เพลงเริ่มหลัง interaction แรกเพื่อผ่าน autoplay policy ของ browser
- ปุ่ม SOUND ON/OFF อยู่มุมขวาบน พร้อม equalizer animation

V7 POLISHED
- เพิ่มตรา Manchester United ตั้งแต่หน้าแรก
- แก้ countdown ไม่ให้เลข 3 แสดงซ้ำ
- ปรับ animation รูป 4 ใบเป็น cinematic slide + blur + soft overshoot และลดช่วง delay

V8 FAN EDITION
- เพิ่มข้อความ FAN-MADE / FOR A UNITED FAN เพื่อสื่อว่าเป็นงานแฟนทำ ไม่ใช่ผลิตภัณฑ์ทางการของสโมสร
- หน้า Memories เปลี่ยนเป็น scroll ลงจริง และรูป 4 รูป reveal ทีละใบเมื่อเลื่อนถึง
- ใช้ IntersectionObserver เพื่อให้ transition ขึ้นกับตำแหน่ง scroll และสมูทกว่า animation ตามเวลา

V9 CINEMATIC
- Countdown ช้าลง: แต่ละเลข ~1.12 วินาที พร้อม enter/hold/exit motion
- ทุก scene ใช้ cinematic red/black shutter transition พร้อมตราสโมสรตรงกลาง
- scene เดิมมี camera push + blur ก่อนเปลี่ยน และ scene ใหม่ค่อย focus เข้า
- Memories ไม่ auto animate อีกต่อไป: ต้อง scroll ให้รูปเข้า viewport ประมาณครึ่งใบก่อน transition จึงเริ่ม
- Memory reveal ช้าลง พร้อม soft rise + focus และภาพมี subtle breathing หลัง reveal
- โลโก้หน้าแรกใหญ่ขึ้นและย้ายมาใกล้ headline ให้เป็นองค์ประกอบเดียวกัน

V10 DIRECTOR'S CUT
- หน้าแรก: โลโก้เป็น watermark ใหญ่บาง ๆ หลัง headline
- หน้า Manchester reveal: ลด opacity โลโก้และขยายเป็น atmospheric background
- transition สลับ 5 แบบ: horizontal wipe, vertical wipe, split, diagonal, zoom cut
- countdown ช้าลงและใช้ continuous enter-hold-exit motion
- Story export เปลี่ยนเป็น JPG 1080x1920 และ embed asset เป็น data URL เพื่อให้กดเซฟได้แม้เปิด index.html ผ่าน file://
