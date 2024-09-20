# Github_Workshop_notSoBasic
มาาาาา เรามาลองเล่น pop, stash, merge อะไรที่ซับซ้อนขึ้นกว่าเดิมหน่อย 👀

## ก่อนเริ่ม ‼️
- อยู่กันเป็นกลุ่ม 2-3 คน (ตามเดิม)
- สร้าง repo ชื่อว่า `GH_notSoBasic_<ชื่อเล่นสาขา_ชื่อเล่นสาขา>`
   - เช่น `GH_notSoBasic_GailCS_JeromeIT`
- clone repo นี้ และเชื่อม remote repo ที่พึ่งสร้าง
- ตั้งสติดี ๆ 👍🏻🙏🏻🛐
- เริ่มทำทีละคน ช่วย ๆ กันทำ

## Recheck อีกรอบก่อนเริ่มทำ
- ✅ gitinit ยัง?
- ✅ Clone Repo / remote connect ยัง?
- ✅ อ่าน `README.md` จบยัง?
- ✅ ทำ [Github_Workshop_Basic](https://github.com/galilynnn/Github_Workshop_Basic) ยัง?

### สำหรับ 🅰️:
1. สร้าง branch ใหม่ 2 อัน:
   - `feature_a`
   - `final_version`
2. ใน branch `feature_a` ให้สร้างไฟล์ `feature_a.txt` และเขียนว่า "นี่คือฟีเจอร์ A สวัสดีจร้า"
3. เพิ่มไฟล์ `note_a.txt` และเขียนข้อความสั้น ๆ ว่า "test test A"
4. Commit ทั้งสองไฟล์ใน branch `feature_a` และ push ขึ้น remote
5. สลับไปที่ branch `final_version` และ merge `feature_a` เข้ากับ `final_version`
6. ถ้ามี conflict ให้แก้ และ commit ซะ ....
7. สลับไปที่ branch `main` และรอ 🅱️ จัดการต่อ

### สำหรับ 🅱️:
1. Fetch repo และเช็ค branch `feature_a` กับ `final_version`
2. สร้าง branch ใหม่ชื่อ `feature_b`
3. ใน branch `feature_b` ให้สร้างไฟล์ `feature_b.txt` และเขียนว่า "นี่คือฟีเจอร์ B โอ้เยโอ้เย"
4. แก้ไขไฟล์ `note_a.txt` โดยเพิ่มข้อความว่า "เอ๊ะ มีการแก้ไข B"
5. Commit ทั้งสองไฟล์ใน branch `feature_b` และ push ขึ้น remote
6. สลับไปที่ branch `final_version` และ stash การเปลี่ยนแปลงใน `feature_b`
7. Merge branch `feature_b` เข้ากับ `final_version`
8. ถ้ามี conflict ให้แก้ และ commit ซะ...
9. Pop เอาค่าที่ stash ไว้กลับมา แล้ว commit การเปลี่ยนแปลง
10. Push branch `final_version` ขึ้น remote

### สำหรับ 🅰️ และ 🅱️ (ร่วมกัน):
1. Fetch repo และเช็คว่า `feature_a` และ `feature_b` merge เข้ากับ `final_version` เรียบร้อยแล้ว
2. Commit สุดท้ายใน branch `final_version`
3. Push ทั้งหมดขึ้น remote
🪦🏴‍☠️

## Recheck หลังทำ
- ❌ ห้ามมีไฟล์อื่น ๆ ใน branch `main`
- ❌ ทำครบทุก requirement รึยัง
- ✅ ส่งลิ้ง repo ในดิสได้เลยจ้า
(ถ้าเสร็จเร็วก็สลับบทกันทำ 🧘🏻‍♀️)
