# ตัวอย่างการใช้งาน Figma

## ตัวอย่างที่ 1: สร้าง Button Component แบบมี Variants

### สถานการณ์
ต้องการสร้าง Button ที่มีหลาย State (Default, Hover, Pressed, Disabled) และหลาย Size (Small, Medium, Large)

### ขั้นตอน

#### 1. สร้าง Button พื้นฐาน
```
1. สร้าง Frame (กด F)
2. ตั้ง Auto Layout (Shift + A)
3. เพิ่ม Text "Button"
4. ตั้งค่า:
   - Padding: 20px (horizontal), 12px (vertical)
   - Corner Radius: 12px
   - Fill: #6366F1 (Primary color)
   - Text: White, 16px, Semi-bold
```

#### 2. สร้างเป็น Component
```
1. เลือก Frame
2. กด Cmd/Ctrl + Alt + K
3. ตั้งชื่อ "Button"
```

#### 3. เพิ่ม Variants
```
1. คลิกขวาที่ Component
2. เลือก "Add variant"
3. สร้าง Variants:

State Property:
- Default
- Hover
- Pressed
- Disabled

Size Property:
- Small (height: 40px, padding: 16px, text: 14px)
- Medium (height: 48px, padding: 20px, text: 16px)
- Large (height: 56px, padding: 24px, text: 18px)
```

#### 4. ปรับแต่งแต่ละ State
```
Default: Primary color
Hover: Primary Dark (#4F46E5)
Pressed: Primary Dark + opacity 90%
Disabled: Gray (#D1D5DB), Text Gray (#9CA3AF)
```

#### 5. ใช้งาน
```
1. ลาก Component ไปใส่ในหน้า
2. เลือก State และ Size จาก Properties panel
3. แก้ Text ตามต้องการ
```

---

## ตัวอย่างที่ 2: สร้าง Navigation Bar แบบ Responsive

### สถานการณ์
สร้าง Navigation Bar ที่ปรับตัวได้ตามขนาดหน้าจอ

### ขั้นตอน

#### 1. สร้าง Nav Container
```
1. สร้าง Frame (กด F)
   - Width: 375px (Mobile)
   - Height: 64px
2. เพิ่ม Auto Layout (Shift + A)
3. ตั้งค่า:
   - Direction: Horizontal
   - Padding: 16px
   - Gap: 16px
   - Alignment: Space between
```

#### 2. เพิ่ม Elements
```
Left Section:
- Logo (40x40px)

Center Section:
- Title "App Name"
- ใช้ Text style: Heading 3

Right Section:
- Icons (Search, Notifications, Profile)
- แต่ละไอคอน 24x24px
```

#### 3. ตั้ง Constraints
```
Logo:
- Left & Top

Title:
- Left & Right (Scale)
- Center vertically

Icons:
- Right & Top
- Fixed size
```

#### 4. ทำให้ Responsive
```
1. Duplicate Frame สำหรับ Tablet และ Desktop
2. ปรับขนาด:
   - Tablet: 768px
   - Desktop: 1440px
3. Elements จะปรับตามโดยอัตโนมัติ
```

---

## ตัวอย่างที่ 3: สร้าง Card List ด้วย Auto Layout

### สถานการณ์
สร้างรายการ Cards ที่สามารถเพิ่มลบได้ง่าย

### ขั้นตอน

#### 1. สร้าง Card Component
```
1. สร้าง Frame
2. เพิ่ม Auto Layout (Vertical)
3. Padding: 16px
4. Gap: 12px
5. Corner Radius: 12px
6. Shadow: 0px 2px 8px rgba(0,0,0,0.08)

Elements:
- Image (Width: Fill, Height: 200px)
- Title (Text style: Heading 3)
- Description (Text style: Body)
- Footer (Date + Category icons)
```

#### 2. สร้าง List Container
```
1. สร้าง Frame ใหม่
2. เพิ่ม Auto Layout (Vertical)
3. Padding: 24px
4. Gap: 16px
5. Width: 375px (หรือตามต้องการ)
```

#### 3. เพิ่ม Cards
```
1. ลาก Card Components เข้า List
2. Duplicate (Cmd/Ctrl + D) เพื่อเพิ่ม Cards
3. Auto Layout จะจัดเรียงและจัดระยะให้เอง
```

#### 4. ทดสอบ
```
- เพิ่ม Card: Duplicate
- ลบ Card: Delete
- เปลี่ยนข้อความ: Card จะปรับขนาดอัตโนมัติ
- ปรับระยะห่าง: เปลี่ยน Gap value
```

---

## ตัวอย่างที่ 4: Prototype Login Flow

### สถานการณ์
สร้าง Prototype แสดงขั้นตอน Login → OTP → Success

### ขั้นตอน

#### 1. สร้าง 3 Frames
```
Frame 1: Login Screen
- Phone Number Input
- "Send OTP" Button

Frame 2: OTP Screen
- OTP Input (6 digits)
- "Verify" Button
- "Resend" Link

Frame 3: Success Screen
- Success icon
- "Login Successful" message
- "Continue" Button
```

#### 2. เชื่อม Prototype
```
Login → OTP:
1. เลือก "Send OTP" Button
2. เปลี่ยนไปที่ Tab "Prototype"
3. ลากเส้นไป Frame "OTP Screen"
4. ตั้งค่า:
   - On Click
   - Navigate to
   - Smart Animate
   - Duration: 300ms

OTP → Success:
1. เลือก "Verify" Button
2. ลากเส้นไป Frame "Success"
3. ตั้งค่า:
   - On Click
   - Navigate to
   - Move In (from right)
   - Duration: 250ms

Success → (กลับหน้าแรก):
1. เลือก "Continue" Button
2. ลากเส้นไป Frame "Login"
3. ตั้งค่า:
   - On Click
   - Navigate to
   - Dissolve
```

#### 3. เพิ่ม Microinteractions
```
Input Focus:
1. Duplicate Input field → สร้าง "Focused" state
2. เปลี่ยน Border color → Primary
3. เพิ่ม Border width → 2px
4. เชื่อม On Click → Navigate to Focused state
5. Animation: Smart Animate

Button Hover:
1. Duplicate Button → สร้าง "Hover" state
2. เปลี่ยนสี → Primary Dark
3. เชื่อม On Hover → Hover state
4. Animation: Instant
```

#### 4. ทดสอบ
```
1. คลิกปุ่ม Play (▶)
2. เลือก Starting Frame
3. ทดสอบการทำงาน
4. ตรวจสอบ Transitions
```

---

## ตัวอย่างที่ 5: สร้าง Dark Mode

### สถานการณ์
สร้าง Design ที่รองรับทั้ง Light และ Dark Mode

### ขั้นตอน

#### 1. วางแผน Color System
```
Light Mode:
- Background: #FFFFFF
- Surface: #F9FAFB
- Text Primary: #111827
- Text Secondary: #6B7280
- Border: #E5E7EB

Dark Mode:
- Background: #111827
- Surface: #1F2937
- Text Primary: #F9FAFB
- Text Secondary: #9CA3AF
- Border: #374151
```

#### 2. สร้าง Color Styles
```
1. สร้าง Color Styles สำหรับ Light:
   - "Light/Background"
   - "Light/Surface"
   - "Light/Text/Primary"
   - "Light/Text/Secondary"
   - "Light/Border"

2. สร้าง Color Styles สำหรับ Dark:
   - "Dark/Background"
   - "Dark/Surface"
   - "Dark/Text/Primary"
   - "Dark/Text/Secondary"
   - "Dark/Border"
```

#### 3. สร้าง Design ด้วย Styles
```
1. สร้าง Frame หนึ่ง (Light Mode)
2. ใช้ Color Styles จาก "Light/" ทั้งหมด
3. ห้าม Hardcode colors
```

#### 4. Duplicate สำหรับ Dark Mode
```
1. Duplicate Frame
2. ตั้งชื่อ "Dark Mode"
3. เลือกทุก Element
4. เปลี่ยนจาก "Light/" Styles → "Dark/" Styles
```

#### 5. Variables (Advanced)
```
Figma มีฟีเจอร์ Variables:
1. สร้าง Color Variables
2. สร้าง Modes: Light, Dark
3. กำหนดค่าสีต่าง Modes
4. Design จะสลับ Mode ได้อัตโนมัติ
```

---

## ตัวอย่างที่ 6: Design Handoff ให้ Developer

### สถานการณ์
เตรียม Design ส่งมอบให้ Developer

### ขั้นตอน

#### 1. เตรียม Design System
```
✓ ทุก Color เป็น Styles
✓ ทุก Text เป็น Text Styles
✓ Components ครบถ้วน
✓ Naming สม่ำเสมอ
```

#### 2. จัดระเบียบ File
```
Structure:
├── 📄 Cover (อธิบาย Project)
├── 📄 Design System
│   ├── Colors
│   ├── Typography
│   ├── Components
│   └── Icons
├── 📄 Screens
│   ├── Onboarding
│   ├── Authentication
│   ├── Home
│   └── ...
└── 📄 Prototype
```

#### 3. Export Assets
```
1. Icons:
   - Format: SVG
   - Naming: icon-name.svg
   - Export: 1x

2. Images:
   - Format: PNG
   - Export: 1x, 2x, 3x
   - Compress ก่อน

3. App Icons:
   - All required sizes
   - iOS: 1024x1024
   - Android: 512x512
```

#### 4. Developer Handoff
```
1. เปิด Dev Mode:
   - คลิก "Dev Mode" toggle
   
2. Developer สามารถดู:
   - CSS/Code snippets
   - Measurements
   - Colors (Hex, RGB, HSL)
   - Fonts
   - Assets ready to download

3. เพิ่ม Annotations:
   - อธิบาย Interactions
   - ระบุ Animations
   - โน้ต Edge cases
```

#### 5. สร้าง Documentation
```
Style Guide Document:
1. Cover Page
2. Color Palette
3. Typography Scale
4. Components Library
5. Spacing System
6. Icons
7. Interaction Patterns
8. Animation Guidelines
```

---

## ตัวอย่างที่ 7: ทำ Animated Loader

### สถานการณ์
สร้าง Loading Animation แบบ Smooth

### ขั้นตอน

#### 1. สร้าง Loader Element
```
1. สร้าง Circle (40x40px)
2. ไม่ต้อง Fill
3. Stroke: 4px, Primary Color
4. Stroke Cap: Round
5. ตั้ง Arc: 270° (เหลือช่องว่าง 90°)
```

#### 2. สร้าง Animation Frames
```
Frame 1: 
- Rotation: 0°

Frame 2:
- Rotation: 45°

Frame 3:
- Rotation: 90°

...

Frame 8:
- Rotation: 315°

Frame 9:
- Rotation: 360° (กลับจุดเริ่มต้น)
```

#### 3. เชื่อม Prototype
```
1. Frame 1 → Frame 2:
   - After Delay (100ms)
   - Smart Animate
   - Ease Out

2. Frame 2 → Frame 3:
   - After Delay (100ms)
   - Smart Animate
   - Ease Out

...

3. Frame 9 → Frame 1:
   - After Delay (100ms)
   - Smart Animate
   - Ease Out
   (สร้าง Loop)
```

#### 4. Alternative: Plugin
```
ใช้ Plugin:
- "Figmotion"
- "LottieFiles"

เพื่อสร้าง Animation แบบละเอียด
Export เป็น Lottie JSON
```

---

## ตัวอย่างที่ 8: Responsive Table Design

### สถานการณ์
สร้างตารางข้อมูลที่ทำงานได้ทั้ง Desktop และ Mobile

### ขั้นตอน

#### Desktop Version
```
1. สร้าง Frame (1440px width)
2. สร้าง Table ด้วย Auto Layout

Structure:
Header Row (Auto Layout Horizontal):
- Column 1: Name (200px)
- Column 2: Email (300px)
- Column 3: Role (150px)
- Column 4: Status (150px)
- Column 5: Actions (100px)

Data Rows (เหมือน Header):
- แต่ละ Row เป็น Auto Layout
- Rows รวมกันด้วย Auto Layout Vertical
```

#### Mobile Version (Card Layout)
```
1. สร้าง Frame (375px width)
2. แปลงแต่ละ Row เป็น Card

Card Structure:
┌─────────────────┐
│ Name (Heading)  │
│ Email           │
│ Role            │
│ Status Badge    │
│ Actions (Icon)  │
└─────────────────┘

Auto Layout Vertical:
- Cards stack vertically
- Gap: 16px
```

---

## Tips สำหรับการใช้งานจริง

### 1. เริ่มจาก Low-Fidelity
```
1. Wireframe ด้วย Rectangles และ Text
2. วางโครงสร้างก่อน
3. ไม่ต้องสน Colors/Styles
4. Focus ที่ Layout และ Flow
```

### 2. Build Design System Early
```
1. สร้าง Colors และ Typography ก่อน
2. สร้าง Components พื้นฐาน (Button, Input)
3. ใช้ Components ตั้งแต่เริ่ม
4. จะ Scale ได้ง่ายกว่า
```

### 3. Use Templates
```
Figma Community มี:
- Design System templates
- Mobile App templates
- UI Kit templates

Fork และปรับใช้ได้เลย
```

### 4. Collaborate Early
```
1. Share ให้ทีมดูตั้งแต่ Wireframe
2. ใช้ Comments รับ Feedback
3. Iterate แต่ละ Version
4. Version History เก็บ Milestones
```

### 5. Test on Real Devices
```
1. ใช้ Figma Mirror app
2. Preview บนมือถือจริง
3. ทดสอบ Touch interactions
4. ตรวจสอบ Readability
```

---

## แหล่งข้อมูลเพิ่มเติม

- [Figma Community - Examples](https://www.figma.com/community)
- [Design System Examples](https://www.figma.com/community/search?model_type=files&q=design%20system)
- [Mobile UI Kits](https://www.figma.com/community/search?model_type=files&q=mobile%20ui%20kit)

