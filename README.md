# 🏍️ HONDA CATALOG - สมุดภาพอะไหล่ฮอนด้า

แคตตาล็อกอะไหล่ฮอนด้า ใช้งานได้ทั้ง **ออนไลน์** และ **ออฟไลน์**

## 📦 โครงสร้างโปรเจค

```
HONDA-CATALOG/
├── online/          # เวอร์ชันออนไลน์ (เชื่อมต่อกับเซิร์ฟเวอร์)
├── offline/         # เวอร์ชันออฟไลน์ (ใช้งานได้ tanpa internet)
└── docs/            # เอกสารประกอบ
```

## 🚀 การใช้งาน

### แบบออฟไลน์ (แนะนำ)

เปิดไฟล์จากโฟลเดอร์ `offline/`:

```bash
# Linux
chromium /home/boy/HONDA-CATALOG/offline/index.html
firefox /home/boy/HONDA-CATALOG/offline/index.html

# Windows
start HONDA-CATALOG\offline\index.html

# macOS
open HONDA-CATALOG/offline/index.html
```

### แบบออนไลน์

เปิดไฟล์จากโฟลเดอร์ `online/`:

```bash
chromium /home/boy/HONDA-CATALOG/online/index.html
```

## 📊 ข้อมูลเว็บไซต์

| รายการ | ค่า |
|--------|-----|
| **ไฟล์ทั้งหมด** | 289 ไฟล์ |
| **ขนาดรวม** | ~16 MB |
| **หน้า HTML** | 37 หน้า |
| **รูปภาพ** | ~70 รูป (Promotion) |
| **CSS/JS** | Bootstrap, Font Awesome, Slick |

## 📋 หมวดหมู่ที่มี

- 🏠 **หน้าหลัก** - แสดงโปรโมชั่นและค้นหาอะไหล่
- 📝 **สมัครสมาชิก** - ลงทะเบียนผู้ใช้ใหม่
- 🔐 **เข้าสู่ระบบ** - Login
- 🛒 **ตะกร้าสินค้า** - เลือกและสั่งซื้ออะไหล่
- 🖼️ **รูปภาพโปรโมชั่น** - โปรโมชั่นทั้งหมด
- 🔍 **ค้นหารุ่นรถ** - เลือกตามรุ่น HONDA

## 🏷️ รุ่นรถที่รองรับ

ADV150, ADV160, ADV350, AIR BLADE, AIR BLADE-i, C125, CB150R, CB300FA, CB300R, CBR150R, CBR250R, CBR250RR, CBR300R, CL300, CLICK110, CLICK110i, CLICK125i, CLICK150i, CLICK160, CRF250L, CRF250M, CRF300L, CT125, CZ-i, DREAM110i, DREAM125, FORZA300, FORZA350, Giorno Plus, ICON, LEAD125, MOOVE, MSX125, MSX GROM, PCX125, PCX150, PCX160, PHANTOM200, REBEL300, SCOOPY, SCOOPY-i, SONIC125, SPACY-i, SUPER CUB, WAVE100X, WAVE100Z, WAVE110i, WAVE110i AT, WAVE125, WAVE125i, WAVE125R, WAVE125S, WAVE125X, ZOOMER-X

## 📝 หมายเหตุ

- **เวอร์ชันออฟไลน์**: ใช้งานได้ทันทีโดยไม่ต้องเชื่อมต่ออินเทอร์เน็ต
- **เวอร์ชันออนไลน์**: ต้องเชื่อมต่ออินเทอร์เน็ต (สำหรับโหลดทรัพยากรจาก CDN)
- ข้อมูลเป็นแบบ Static (ดาวน์โหลดมาจากเว็บไซต์)
- ไม่สามารถสั่งซื้อจริงได้ (เป็นเพียงカタログสำหรับดูข้อมูล)

## 📄 License

โครงการนี้สร้างเพื่อการศึกษาและใช้งานส่วนตัว

## 🔗 แหล่งที่มา

เว็บไซต์ต้นฉบับ: https://www.suparat.net/pssretail/

---

**สร้างเมื่อ:** 03/03/2025
**โดย:** HONDA PSSRE Offline Project
