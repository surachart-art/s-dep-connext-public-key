# Git PublicKey Setup

หลังจากที่ NDID ได้ลงทะเบียนอนุมัติสิทธิ์การใช้งานระบบ S-DEP-Connext ให้กับสมาชิกเรียบร้อยแล้ว
สมาชิกจะได้รับสิทธิ์การเข้าถึง Github Repository ของ NDID (สำหรับจัดการ Public Key ของ S-DEP-Connext)
ซึ่งสมาชิกจะต้องทำการเพิ่ม Public Key ของตนเองลงใน Github Repository ของ NDID
โดยสามารถทำตามขั้นตอนดังนี้

1. เข้าไปที่หน้า Github Repository ของ NDID
2. กดปุ่ม Add file > Create new file เพื่อเพิ่มไฟล์ Public Key ของตนเองลงใน Repository
3. ตั้งชื่อไฟล์ Public Key โดยใช้รูปแบบ `<ชื่อหน่วยงาน>_public.pem` เช่น `example_company_public.pem`
4. คัดลอกเนื้อหาของไฟล์ Public Key ที่ได้สร้างไว้ในขั้นตอนการเตรียมสิ่งที่ต้องใช้สำหรับการติดตั้งระบบ S-DEP-Connext
5. กดปุ่ม Commit changes.. เพื่อขอบันทึกไฟล์ Public Key ลงใน Repository
6. กดปุ่ม Propose changes
7. กดปุ่ม Create pull request
8. เมื่อสร้าง Pull request เรียบร้อยแล้ว ให้รอการตรวจสอบและอนุมัติจาก NDID
9. เมื่อ NDID อนุมัติ Pull request แล้ว Public Key ของสมาชิกจะถูกเพิ่มลงในระบบ S-DEP-Connext
