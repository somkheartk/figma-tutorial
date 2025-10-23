# คำถามที่พบบ่อย (FAQ)

## คำถามทั่วไป

### 1. Figma ใช้ได้ฟรีหรือไม่?

**คำตอบ:** ใช้ได้ฟรี! Figma มีแผนฟรีที่เหมาะสำหรับการเริ่มต้นและโปรเจคส่วนตัว

**Free Plan ได้อะไรบ้าง:**
- 3 Figma files และ 3 FigJam files
- Collaborators ไม่จำกัด
- Plugins และ Templates
- Mobile app (iOS/Android)
- Version history 30 วัน

**Professional Plan ($12/editor/month):**
- Files ไม่จำกัด
- Version history ไม่จำกัด
- Private projects
- Shared libraries
- Team libraries

### 2. ต้องติดตั้งโปรแกรมหรือไม่?

**คำตอบ:** ไม่จำเป็น! Figma ทำงานบน Web Browser (Chrome, Firefox, Safari, Edge)

แต่ถ้าต้องการ ก็มี Desktop App สำหรับ:
- macOS
- Windows
- Linux (Beta)

**Desktop App ดีกว่ายังไง:**
- ใช้ Font ในเครื่องได้
- เร็วกว่าเล็กน้อย
- ทำงานได้แม้ไม่มีเน็ต (ฟีเจอร์บางอย่าง)

### 3. Figma ต่างจาก Adobe XD, Sketch ยังไง?

**Figma:**
- ทำงานบน Browser/Cloud
- Collaboration แบบ Real-time
- Cross-platform (Mac, Windows, Linux)
- Version control ในตัว

**Adobe XD:**
- ติดตั้งในเครื่อง
- มี Creative Cloud integration
- Auto-animate ทำได้ง่าย

**Sketch:**
- macOS เท่านั้น
- Plugin ecosystem ใหญ่มาก
- Native app เร็วกว่า

---

## คำถามเกี่ยวกับการใช้งาน

### 4. ทำไม Font บางตัวใช้ไม่ได้?

**สาเหตุ:**
- Font ไม่ได้ติดตั้งในเครื่อง
- ใช้ Web version และ Font เป็น Local font

**วิธีแก้:**
1. ติดตั้ง Figma Font Helper (สำหรับ Web version)
2. ใช้ Desktop App (อ่าน Local fonts ได้)
3. Upload font เป็น Web font
4. ใช้ Google Fonts (มีให้เลือกมากมาย)

### 5. จะ Export รูปภาพออกมายังไง?

**วิธี Export:**

**Export ทีละ Object:**
1. เลือก Object ที่ต้องการ
2. ไปที่ Panel ขวา → Export section
3. เลือกรูปแบบ (PNG, JPG, SVG, PDF)
4. กำหนด Scale (1x, 2x, 3x)
5. คลิก Export

**Export หลาย Objects:**
1. เลือกหลาย Objects พร้อมกัน
2. Right-click → Export
3. เลือก settings
4. Export all

**รูปแบบไฟล์แนะนำ:**
- **PNG**: รูปภาพทั่วไป, ต้องการความชัดเจน
- **JPG**: รูปถ่าย, ไฟล์เล็ก
- **SVG**: Icons, logos, vector graphics
- **PDF**: พิมพ์เอกสาร

### 6. Auto Layout คืออะไร? ใช้ยังไง?

**Auto Layout** = ระบบจัดการ Layout อัตโนมัติ

**ประโยชน์:**
- ปรับขนาดตามเนื้อหา
- จัดระยะห่างสม่ำเสมอ
- ทำ Responsive Design ง่าย

**วิธีใช้:**
1. เลือก Frame/Group
2. กด `Shift + A`
3. ตั้งค่า:
   - Direction: Horizontal/Vertical
   - Padding: ระยะห่างด้านใน
   - Gap: ระยะห่างระหว่าง Items
   - Alignment: จัดเรียง

**Use Cases:**
- Buttons ที่ขยายตามข้อความ
- Lists ที่เพิ่มลบ items ได้
- Cards ที่ปรับขนาดอัตโนมัติ

### 7. Component กับ Frame ต่างกันยังไง?

**Frame:**
- Container พื้นฐาน
- เหมือน Artboard
- ใช้สำหรับหน้าจอ/Section

**Component:**
- Element ที่ใช้ซ้ำได้
- แก้ Master จะอัพเดททุก Instance
- มี Variants ได้

**เมื่อไหร่ใช้ Component:**
- Buttons, Icons
- Navigation bars
- Cards, Lists
- Input fields
- อะไรก็ตามที่ใช้ซ้ำ

### 8. จะทำ Responsive Design ยังไง?

**วิธีทำ:**

**1. ใช้ Constraints:**
- กำหนดว่า Element ยึดกับขอบไหน
- Scale or Fix size
- ตัวอย่าง: Logo ยึด Top-Left, Button ยึด Center

**2. ใช้ Auto Layout:**
- Frame ขยายตามเนื้อหาอัตโนมัติ
- Gap และ Padding คงที่

**3. สร้างหลาย Breakpoints:**
- Mobile: 375px
- Tablet: 768px
- Desktop: 1440px
- ใช้ Constraints ให้เหมือนกัน

**4. ใช้ % Width:**
- แทนที่จะใช้ Fixed width
- Element จะขยายตามหน้าจอ

---

## คำถามเกี่ยวกับ Prototype

### 9. จะทำ Prototype Interactive ยังไง?

**ขั้นตอน:**

1. **สลับไปที่ Prototype Mode:**
   - คลิก Tab "Prototype" ที่ Properties panel

2. **สร้าง Connection:**
   - เลือก Element (เช่น Button)
   - ลากจุดสีฟ้าไปยัง Frame ปลายทาง

3. **ตั้งค่า Interaction:**
   - **Trigger**: On Click, On Hover, After Delay, etc.
   - **Action**: Navigate to, Open overlay, etc.
   - **Animation**: Instant, Dissolve, Move in, Smart animate

4. **ทดสอบ:**
   - คลิกปุ่ม Play (▶) ที่มุมบนขวา
   - ลอง Interact กับ Prototype

**Smart Animate Tips:**
- ใช้ชื่อ Layer เดียวกันในทั้ง 2 Frames
- Figma จะ Animate การเปลี่ยนแปลงโดยอัตโนมัติ

### 10. จะแชร์ Prototype ให้คนอื่นดูยังไง?

**วิธีแชร์:**

1. **คลิกปุ่ม Share** (มุมบนขวา)

2. **เลือกประเภท:**
   - **Anyone with the link**: ใครก็ได้ที่มีลิงก์
   - **Invited people**: เฉพาะคนที่เชิญ

3. **เลือกสิทธิ์:**
   - **Can view**: ดูอย่างเดียว
   - **Can edit**: แก้ไขได้
   - **Can view prototype**: ดู Prototype ได้

4. **Copy link และส่งให้คนอื่น**

**Prototype Settings:**
- Starting frame
- Device frame (แสดงกรอบมือถือ)
- Background color
- Show hotspots (แสดงจุดที่คลิกได้)

---

## คำถามเกี่ยวกับ Collaboration

### 11. จะทำงานร่วมกับทีมยังไง?

**Team Collaboration:**

1. **สร้าง Team:**
   - Dashboard → Create Team
   - เชิญสมาชิก

2. **แชร์ไฟล์:**
   - Share → Invite members
   - กำหนดสิทธิ์ (View/Edit)

3. **คอมเมนต์:**
   - กด `C` เพื่อแสดง Comment tool
   - คลิกจุดที่ต้องการคอมเมนต์
   - พิมพ์ข้อความ
   - Tag คนอื่นด้วย `@name`

4. **Live Collaboration:**
   - เห็น Cursor คนอื่นแบบ Real-time
   - เห็นว่าใครกำลังแก้อะไร

**Best Practices:**
- ตั้งชื่อ Layer ให้ชัด
- ใช้ Comments แทน Chat ส่วนตัว
- Review และ Resolve comments
- ใช้ Version History เก็บ Milestones

### 12. Version History ทำงานยังไง?

**Version History** = บันทึกการเปลี่ยนแปลงอัตโนมัติ

**วิธีดู:**
1. File name dropdown (บนซ้าย)
2. Show version history
3. เลือก Version ที่ต้องการดู

**วิธีเซฟ Version:**
1. File name dropdown
2. Save to version history
3. ตั้งชื่อและใส่ Description
4. Save

**Restore Version:**
1. เลือก Version ที่ต้องการ
2. คลิก "Restore this version"
3. จะสร้าง Version ใหม่จากอันเก่า

---

## คำถามเกี่ยวกับ Performance

### 13. ไฟล์ช้า/หนัก แก้ยังไง?

**สาเหตุและวิธีแก้:**

**1. รูปภาพขนาดใหญ่:**
- ✅ ลดขนาดรูปก่อน Import
- ✅ ใช้รูปไม่เกิน 4096px
- ✅ Compress รูปก่อน

**2. Layer มากเกินไป:**
- ✅ ลบ Hidden layers
- ✅ Flatten vector ที่ซับซ้อน
- ✅ รวม Shapes ที่ไม่ได้แก้แล้ว

**3. Effects มากเกินไป:**
- ✅ ลด Blur effects
- ✅ ใช้ Styles แทนการตั้งค่าแยก
- ✅ ลด Shadows ที่ซ้อนกัน

**4. Components ซ้อนลึก:**
- ✅ Detach instances ที่ไม่จำเป็น
- ✅ แบ่งไฟล์ใหญ่เป็นหลายไฟล์

### 14. จะ Backup ไฟล์ยังไง?

**Figma ทำ Auto-save:**
- เซฟทุกการเปลี่ยนแปลงอัตโนมัติ
- Version history เก็บทุกเวอร์ชัน

**Backup เพิ่มเติม:**

**1. Duplicate File:**
- File menu → Duplicate
- เก็บใน Project ต่างหาก

**2. Export File:**
- File → Save local copy (.fig file)
- เก็บไว้ในเครื่อง

**3. Use Version History:**
- เซฟ Named versions ตอน Milestone สำคัญ

---

## คำถามเกี่ยวกับ Mobile Design

### 15. Frame Size ไหนที่นิยมใช้?

**iOS:**
- iPhone 14 Pro: 393 x 852
- iPhone 14 Pro Max: 430 x 932
- iPhone SE: 375 x 667
- iPad Pro 11": 834 x 1194

**Android:**
- Pixel 7: 412 x 915
- Samsung Galaxy S23: 360 x 780
- Common: 360 x 800 (Base)

**Recommendations:**
- เริ่มที่ 375 x 812 (Base iPhone)
- ทำ Responsive design ที่ปรับตัวได้
- Test หลาย Sizes

### 16. Status Bar ใช้ยังไง?

**วิธีเพิ่ม Status Bar:**

**1. ใช้ Resource พร้อมใช้:**
- Figma Community → "Status bar"
- Import component มาใช้

**2. สร้างเอง:**
```
Elements:
- Time (left): 9:41 AM
- Icons (right): Signal, WiFi, Battery
- Height: 44px (iOS), 24px (Android)
- Background: ตามธีมของแอป
```

**iOS Status Bar:**
- Light: ไอคอนขาว (บนพื้นหลังมืด)
- Dark: ไอคอนดำ (บนพื้นหลังสว่าง)

**Android Status Bar:**
- มี Navigation buttons ด้านล่าง
- Back, Home, Recent apps

---

## Troubleshooting

### 17. Plugin ติดตั้งไม่ได้

**วิธีแก้:**
1. ใช้ Desktop App แทน Web version
2. Clear browser cache
3. ลอง Browser อื่น
4. ตรวจสอบ Network/Firewall

### 18. ไม่สามารถ Save/Export ได้

**วิธีแก้:**
1. ตรวจสอบ Internet connection
2. Refresh page
3. Check permissions (view-only?)
4. ลอง Export format อื่น
5. Restart Figma

### 19. Font หายหรือผิดเพี้ยน

**วิธีแก้:**
1. ติดตั้ง Missing fonts
2. ใช้ Desktop app
3. ติดตั้ง Figma Font Helper
4. Replace fonts ที่หาย

---

## คำถามอื่นๆ

### 20. หาแรงบันดาลใจในการออกแบบได้จากไหน?

**แหล่งแรงบันดาลใจ:**

**Design Galleries:**
- Dribbble
- Behance
- Awwwards
- Mobbin (Mobile patterns)

**Figma Resources:**
- Figma Community
- Templates
- UI kits

**Design Systems:**
- Material Design (Google)
- Human Interface Guidelines (Apple)
- Carbon Design System (IBM)
- Ant Design

**Follow Designers:**
- Twitter/X: #UIDesign, #MobileDesign
- Instagram: UI/UX designers
- YouTube: Design channels

### 21. มี Course หรือคอร์สเรียนแนะนำไหม?

**Free Resources:**
- Figma Official Tutorial
- YouTube: Figma channel
- Figma Community tutorials

**Paid Courses:**
- Udemy: "Complete Web & Mobile Designer"
- Coursera: UI/UX Design Specialization
- Skillshare: Figma classes

**Thai Resources:**
- Facebook Groups: Figma Thailand
- YouTube: ช่อง Design ภาษาไทย
- อบรม/Workshop ต่างๆ

### 22. จะเป็น UI/UX Designer ต้องทำยังไง?

**Roadmap:**

**1. เรียนรู้พื้นฐาน:**
- Design principles
- Color theory
- Typography
- Layout และ Composition

**2. ฝึกใช้ Tools:**
- Figma (หลัก)
- Adobe XD, Sketch (ทางเลือก)
- Photoshop/Illustrator (ช่วยเหลือ)

**3. เรียนรู้ UX:**
- User research
- Wireframing
- Prototyping
- Usability testing

**4. สร้าง Portfolio:**
- Case studies 3-5 โปรเจค
- แสดง Process ไม่ใช่แค่ผลงาน
- Personal projects หรือ Redesigns

**5. Practice:**
- Daily UI Challenge
- Redesign แอปที่ใช้ประจำ
- ทำโปรเจคส่วนตัว
- เข้า Design communities

**6. เรียนรู้เพิ่มเติม:**
- HTML/CSS basics
- Design systems
- Accessibility
- Interaction design

---

หากมีคำถามเพิ่มเติม สามารถ:
- เปิด Issue ใน GitHub repository
- ถามใน Figma Community
- Join Facebook Group: Figma Thailand
