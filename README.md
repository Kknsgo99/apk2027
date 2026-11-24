# บันทึกคะแนนสอบ (APK)
1. สร้าง repo ใหม่บน GitHub แล้วอัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ (รวมโฟลเดอร์ .github)
2. แท็บ Actions → Build APK → Run workflow (หรือรอให้รันเองหลัง push)
3. เมื่อเสร็จ ดาวน์โหลด Artifact "score-app-apk" → แตก zip ได้ app-debug.apk
4. ส่งไฟล์เข้าโทรศัพท์ เปิดติดตั้ง (อนุญาต "ติดตั้งจากแหล่งที่ไม่รู้จัก")
เชื่อม Google Sheet: ในแอปกด ⚙ Google Sheet แล้ววาง URL Web app (.../exec) จาก code.gs
