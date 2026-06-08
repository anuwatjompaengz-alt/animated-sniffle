# Security Policy 🛡️

## Reporting a Vulnerability

หากคุณพบช่องโหว่ด้านความปลอดภัย โปรดรายงานให้เรารู้แบบเป็นส่วนตัว

### วิธีรายงาน:
1. **อย่ารายงานในที่สาธารณะ** (Issues/Discussions)
2. ติดต่อผู้ดูแล Repository ผ่านทาง:
   - GitHub Security Advisory
   - Email: [Contact maintainer]
3. ให้รายละเอียด:
   - อธิบายช่องโหว่
   - วิธีทำซ้ำ
   - ผลกระทบที่เป็นไปได้

### Response Timeline:
- ✅ ยอมรับภายใน 48 ชั่วโมง
- ✅ ตรวจสอบและแก้ไขภายใน 7 วัน
- ✅ เปิดตัว patch ภายใน 14 วัน

---

## Security Best Practices

ทีมของเรามุ่งมั่นในการตรวจสอบความปลอดภัยอย่างต่อเนื่อง:

### Code Review
- ✅ ทุก Pull Request ต้องได้ approval จากอย่างน้อย 1 คน
- ✅ ตรวจสอบความปลอดภัยเป็นส่วนหนึ่งของ review

### Dependencies
- ✅ ใช้ Dependabot เพื่ออัปเดตอัตโนมัติ
- ✅ ตรวจสอบช่องโหว่ใหม่อยู่เสมอ

### Secrets
- ❌ ห้ามใส่ API keys, passwords ในโค้ด
- ✅ ใช้ Environment Variables แทน
- ✅ ใช้ GitHub Secrets สำหรับ CI/CD

### Testing
- ✅ ต้องมี Unit Tests
- ✅ ต้องมี Security Tests

---

## Supported Versions

| Version | Supported |
|---------|-----------|
| Latest  | ✅        |
| -1      | ✅        |
| < -1    | ❌        |

---

## Contact

สำหรับคำถามด้านความปลอดภัย โปรดติดต่อผู้ดูแล Repository นี้
