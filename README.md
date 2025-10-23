# คู่มือสอน Figma: จากเริ่มต้นจนออกแบบ Mobile App

## สารบัญ

1. [แนะนำ Figma](#แนะนำ-figma)
2. [เริ่มต้นใช้งาน Figma](#เริ่มต้นใช้งาน-figma)
3. [พื้นฐานของ Figma](#พื้นฐานของ-figma)
4. [เครื่องมือสำคัญใน Figma](#เครื่องมือสำคัญใน-figma)
5. [หลักการออกแบบ UI/UX](#หลักการออกแบบ-uiux)
6. [การออกแบบ Mobile App ทีละขั้นตอน](#การออกแบบ-mobile-app-ทีละขั้นตอน)
7. [Tips และ Best Practices](#tips-และ-best-practices)
8. [แหล่งเรียนรู้เพิ่มเติม](#แหล่งเรียนรู้เพิ่มเติม)

---

## แนะนำ Figma

### Figma คืออะไร?

Figma เป็นเครื่องมือออกแบบ UI/UX แบบออนไลน์ที่ทำงานผ่าน Web Browser โดยไม่ต้องติดตั้งโปรแกรม มีจุดเด่นที่การทำงานร่วมกันแบบ Real-time และการใช้งานที่ง่ายดาย

### ทำไมต้องเลือก Figma?

- **ทำงานบน Cloud**: เข้าถึงได้ทุกที่ ทุกเวลา ไม่ต้องกังวลเรื่องการ Sync ไฟล์
- **Collaboration แบบ Real-time**: หลายคนทำงานในไฟล์เดียวกันได้พร้อมกัน
- **ฟรีสำหรับการใช้งานพื้นฐาน**: เหมาะสำหรับผู้เริ่มต้นและโปรเจคเล็ก
- **ใช้งานง่าย**: Interface ที่เข้าใจง่าย เหมาะสำหรับทั้งมือใหม่และมืออาชีพ
- **Community ใหญ่**: มี Plugin และ Template มากมายให้เลือกใช้

---

## เริ่มต้นใช้งาน Figma

### ขั้นตอนที่ 1: สมัครสมาชิก

1. เข้าไปที่ [figma.com](https://www.figma.com)
2. คลิก "Sign up" หรือ "Get started"
3. สมัครด้วย Email, Google Account หรือ SSO
4. ยืนยัน Email (ถ้าใช้การสมัครแบบ Email)

### ขั้นตอนที่ 2: ทำความรู้จัก Interface

เมื่อเข้าสู่ Figma จะพบกับส่วนต่างๆ ดังนี้:

#### หน้าจอหลัก (Dashboard)
- **Recents**: ไฟล์ที่เปิดล่าสุด
- **Drafts**: ไฟล์ส่วนตัว
- **Teams**: โปรเจคที่ทำงานร่วมกับทีม
- **Community**: Template และ Resource จากชุมชน

#### หน้าจอการทำงาน (Canvas)
- **Toolbar** (บนสุด): เครื่องมือสร้างและแก้ไข
- **Layers Panel** (ซ้าย): แสดงโครงสร้างของ Layer
- **Properties Panel** (ขวา): แสดงคุณสมบัติของ Object ที่เลือก
- **Canvas** (กลาง): พื้นที่ทำงานหลัก

### ขั้นตอนที่ 3: สร้างไฟล์แรก

1. คลิก "+ New" ที่มุมบนซ้าย
2. เลือก "Design file"
3. ตั้งชื่อไฟล์ เช่น "My First Design"

---

## พื้นฐานของ Figma

### 1. Frames vs Groups

#### Frame
- เหมือนกับ Artboard ใน Adobe XD หรือ Sketch
- มี Constraints และ Layout Grid
- ใช้สำหรับกำหนดขนาดหน้าจอ (เช่น iPhone 14, iPad, Desktop)
- สามารถทำ Prototype ได้

**วิธีสร้าง**: กด `F` หรือเลือก Frame tool จาก Toolbar

#### Group
- ใช้จัดกลุ่ม Elements ที่เกี่ยวข้องกัน
- ไม่มี Background หรือ Constraints
- เบากว่า Frame

**วิธีสร้าง**: เลือก Objects หลายๆ อัน แล้วกด `Cmd/Ctrl + G`

### 2. Shapes และ Objects

Figma มี Shape พื้นฐาน ได้แก่:
- **Rectangle** (`R`): สี่เหลี่ยม
- **Ellipse** (`O`): วงกลม/วงรี
- **Line** (`L`): เส้นตรง
- **Arrow**: ลูกศร
- **Polygon**: รูปหลายเหลี่ยม
- **Star**: ดาว
- **Text** (`T`): ข้อความ

### 3. Properties สำคัญ

#### Fill (สี)
- Solid Color: สีเดียว
- Linear Gradient: ไล่สีแบบเส้นตรง
- Radial Gradient: ไล่สีแบบวงกลม
- Image: ใช้รูปภาพเป็น Fill

#### Stroke (เส้นขอบ)
- Inside: เส้นขอบด้านใน
- Outside: เส้นขอบด้านนอก
- Center: เส้นขอบตรงกลาง

#### Effects
- Drop Shadow: เงา
- Inner Shadow: เงาด้านใน
- Layer Blur: เบลอ Layer
- Background Blur: เบลอพื้นหลัง

---

## เครื่องมือสำคัญใน Figma

### 1. Auto Layout

Auto Layout เป็นฟีเจอร์ที่ช่วยจัดการระยะห่างและการจัดเรียงองค์ประกอบอัตโนมัติ

**ข้อดี**:
- ปรับขนาดตามเนื้อหาอัตโนมัติ
- จัดระยะห่างสม่ำเสมอ
- ทำให้ Design เป็น Responsive

**วิธีใช้**:
1. เลือก Frame หรือ Group
2. กด `Shift + A` หรือคลิก "+" ใน Auto Layout
3. ตั้งค่า Direction (Horizontal/Vertical)
4. กำหนด Padding และ Gap

### 2. Components

Components คือ Elements ที่สามารถนำไปใช้ซ้ำได้ เมื่อแก้ไข Master Component จะอัพเดททุก Instance อัตโนมัติ

**ประเภทของ Components**:
- **Master Component**: ต้นฉบับ (มีไอคอนสีม่วง ◆)
- **Instance**: สำเนา (มีไอคอนสีม่วง ◇)

**วิธีสร้าง**:
1. เลือก Object ที่ต้องการ
2. กด `Cmd/Ctrl + Alt + K` หรือคลิกขวาเลือก "Create Component"
3. ตั้งชื่อ Component

**Variants**: สร้าง Component ที่มีหลาย State (เช่น Button: Default, Hover, Pressed)

### 3. Styles

Styles ช่วยให้การจัดการสี ข้อความ และ Effects เป็นมาตรฐานเดียวกัน

**ประเภท Styles**:
- **Color Styles**: ชุดสี
- **Text Styles**: รูปแบบข้อความ
- **Effect Styles**: เอฟเฟกต์
- **Grid Styles**: Grid Layout

**วิธีสร้าง Color Style**:
1. เลือก Object ที่มีสีที่ต้องการ
2. คลิกที่ไอคอน "Style" ใน Fill section
3. คลิก "+" และตั้งชื่อ เช่น "Primary Color"

### 4. Constraints

Constraints กำหนดว่า Element จะเคลื่อนที่หรือเปลี่ยนขนาดอย่างไรเมื่อ Parent Frame เปลี่ยนแปลง

**ตัวเลือก**:
- Left, Right, Center (แนวนอน)
- Top, Bottom, Center (แนวตั้ง)
- Scale: ขยายตามสัดส่วน

### 5. Prototype

Prototype ช่วยสร้างการทำงานแบบ Interactive เพื่อทดสอบ User Flow

**ขั้นตอน**:
1. เปลี่ยนไปที่ Tab "Prototype" (ด้านขวา)
2. เลือก Element ที่ต้องการให้คลิกได้
3. ลากเส้นจุดสีฟ้าไปยัง Frame ปลายทาง
4. เลือก Interaction (On Click, On Hover, etc.)
5. เลือก Animation (Instant, Dissolve, Smart Animate, etc.)

---

## หลักการออกแบบ UI/UX

### 1. ทำความเข้าใจผู้ใช้

- **User Research**: ศึกษาความต้องการและพฤติกรรมของผู้ใช้
- **User Persona**: สร้างโปรไฟล์ผู้ใช้จำลอง
- **User Journey**: วิเคราะห์การใช้งานตั้งแต่ต้นจนจบ

### 2. หลัก Visual Design

#### Hierarchy (ลำดับความสำคัญ)
- ใช้ขนาดตัวอักษรแสดงความสำคัญ
- สีและ Contrast เน้นจุดสำคัญ
- ระยะห่างแยกกลุ่มเนื้อหา

#### Consistency (ความสม่ำเสมอ)
- ใช้สี Font และ Style เดียวกันทั้งแอป
- Components และ Patterns ที่เหมือนกัน
- ระยะห่างและ Spacing ที่สม่ำเสมอ

#### White Space
- ให้พื้นที่ว่างเพียงพอ
- ช่วยให้อ่านง่าย ไม่รกตา
- เน้นเนื้อหาสำคัญ

### 3. Mobile Design Principles

- **Touch Target**: ปุ่มควรมีขนาดอย่างน้อย 44x44pt
- **Thumb Zone**: วางปุ่มสำคัญในพื้นที่เอื้อม
- **Readability**: ตัวอักษรอย่างน้อย 16px สำหรับเนื้อหา
- **Orientation**: รองรับทั้ง Portrait และ Landscape

---

## การออกแบบ Mobile App ทีละขั้นตอน

### โปรเจคตัวอย่าง: แอปรายการสิ่งที่ต้องทำ (To-Do App)

### ขั้นตอนที่ 1: เตรียมความพร้อม

#### 1.1 วางแผนโครงสร้าง
- หน้า Splash Screen
- หน้า Login/Register
- หน้า Task List (หลัก)
- หน้า Add/Edit Task
- หน้า Profile/Settings

#### 1.2 กำหนด Design System
```
Colors:
- Primary: #6366F1 (Indigo)
- Secondary: #8B5CF6 (Purple)
- Success: #10B981 (Green)
- Error: #EF4444 (Red)
- Background: #F9FAFB (Light Gray)
- Text: #111827 (Dark Gray)

Typography:
- Heading 1: 32px, Bold
- Heading 2: 24px, Semi-bold
- Heading 3: 20px, Semi-bold
- Body: 16px, Regular
- Caption: 14px, Regular

Spacing:
- Base unit: 8px
- Small: 8px
- Medium: 16px
- Large: 24px
- XLarge: 32px
```

### ขั้นตอนที่ 2: สร้าง Design System

#### 2.1 สร้าง Color Styles
1. สร้าง Rectangle
2. เติมสี Primary (#6366F1)
3. คลิก Style icon → Create Color Style
4. ตั้งชื่อ "Primary"
5. ทำซ้ำกับสีอื่นๆ

#### 2.2 สร้าง Text Styles
1. สร้าง Text element
2. ตั้งค่า Font, Size, Weight
3. คลิก Style icon → Create Text Style
4. ตั้งชื่อ เช่น "Heading 1"

#### 2.3 สร้าง Components พื้นฐาน

**Button Component**:
1. สร้าง Rectangle (Auto Layout)
2. ขนาด: ความสูง 48px
3. Padding: 16px (ซ้าย-ขวา), 12px (บน-ล่าง)
4. Corner Radius: 12px
5. เพิ่ม Text "Button"
6. สร้างเป็น Component
7. สร้าง Variants: Primary, Secondary, Disabled

**Input Field Component**:
1. สร้าง Frame (Auto Layout)
2. ขนาด: ความสูง 48px
3. เพิ่ม Text placeholder
4. Border: 1px, สี #E5E7EB
5. Corner Radius: 8px
6. Padding: 12px
7. สร้างเป็น Component

### ขั้นตอนที่ 3: สร้าง Frames สำหรับแต่ละหน้า

1. กด `F` เพื่อสร้าง Frame
2. เลือก "Phone" → "iPhone 14 Pro" (393 x 852)
3. ตั้งชื่อ Frame เช่น "Splash Screen"
4. ทำซ้ำสำหรับทุกหน้า

### ขั้นตอนที่ 4: ออกแบบหน้า Splash Screen

1. **Background**:
   - เติมสี Primary gradient
   - จาก #6366F1 ไปยัง #8B5CF6

2. **Logo/Icon**:
   - วาดไอคอนหรือใส่โลโก้กลางหน้าจอ
   - ขนาดประมาณ 120x120px

3. **App Name**:
   - Text style: Heading 1
   - สีขาว
   - จัดกลาง

4. **Loading Indicator** (optional):
   - เพิ่ม Progress bar หรือ Spinner

### ขั้นตอนที่ 5: ออกแบบหน้า Login

#### Layout:
```
┌─────────────────────┐
│                     │
│   [App Logo]        │
│                     │
│   Welcome Back      │ <- Heading
│   Please login      │ <- Subtitle
│                     │
│   [Email Input]     │
│   [Password Input]  │
│                     │
│   [Login Button]    │
│                     │
│   Don't have        │
│   an account?       │
│   [Sign Up]         │
│                     │
└─────────────────────┘
```

#### สร้าง:
1. เพิ่ม Auto Layout Frame เป็น Container
2. Padding: 24px
3. Gap: 16px
4. Direction: Vertical

5. **เพิ่มองค์ประกอบ**:
   - Logo (120x120px, จัดกลาง)
   - Heading "Welcome Back" (Text Style: Heading 2)
   - Subtitle "Please login to continue"
   - Input Field Component (Email)
   - Input Field Component (Password)
   - Button Component (Login)
   - Text + Link สำหรับ Sign Up

### ขั้นตอนที่ 6: ออกแบบหน้า Task List (หน้าหลัก)

#### Layout:
```
┌─────────────────────┐
│ ☰  My Tasks    👤   │ <- Header
├─────────────────────┤
│                     │
│ [ Tab: All ]        │ <- Tabs
│ [ Tab: Active ]     │
│ [ Tab: Done ]       │
│                     │
│ ┌─────────────────┐ │
│ │ □ Task Title    │ │ <- Task Card
│ │   Description   │ │
│ │   📅 Date      │ │
│ └─────────────────┘ │
│                     │
│ ┌─────────────────┐ │
│ │ ✓ Task Title    │ │
│ │   Description   │ │
│ │   📅 Date      │ │
│ └─────────────────┘ │
│                     │
└─────────────────────┘
        [+] <- FAB
```

#### สร้าง:

**1. Header (Auto Layout)**:
- Height: 64px
- Padding: 16px
- Items: Menu icon, "My Tasks" text, Profile icon

**2. Tab Bar**:
- สร้าง Tabs โดยใช้ Auto Layout
- Gap: 8px
- Tabs: All, Active, Completed

**3. Task Card Component**:
```
Card Container (Auto Layout):
  - Background: White
  - Corner Radius: 12px
  - Padding: 16px
  - Drop Shadow
  
  Elements:
  - Checkbox (24x24px)
  - Title (Text Style: Body, Bold)
  - Description (Text Style: Caption)
  - Date with icon
  - Priority indicator (color dot)
```

**4. Floating Action Button (FAB)**:
- Circle: 56x56px
- สี Primary
- Icon: "+" (Plus)
- Position: Bottom Right (24px margin)
- Drop Shadow

### ขั้นตอนที่ 7: ออกแบบหน้า Add/Edit Task

#### Layout:
```
┌─────────────────────┐
│ ← Add Task      ✓   │ <- Header
├─────────────────────┤
│                     │
│ Task Title          │
│ [Input Field]       │
│                     │
│ Description         │
│ [Text Area]         │
│                     │
│ Due Date            │
│ [Date Picker]       │
│                     │
│ Priority            │
│ ○ High ◉ Medium     │
│ ○ Low               │
│                     │
│ Category            │
│ [Dropdown]          │
│                     │
└─────────────────────┘
```

#### สร้าง:
1. Header bar พร้อม Back button และ Save button
2. Form container (Auto Layout, Vertical)
3. Label + Input Field pairs
4. Radio buttons สำหรับ Priority
5. Dropdown สำหรับ Category

### ขั้นตอนที่ 8: สร้าง Prototype

#### เชื่อมโยงหน้าจอ:

1. **Splash → Login**:
   - Interaction: After Delay (2000ms)
   - Animation: Dissolve

2. **Login → Task List**:
   - Trigger: Login button On Click
   - Animation: Move In (Right)

3. **Task List → Add Task**:
   - Trigger: FAB button On Click
   - Animation: Move In (Up)

4. **Add Task → Task List**:
   - Trigger: Back button On Click
   - Animation: Move Out (Down)
   - Trigger: Save button On Click
   - Animation: Move Out (Down)

5. **Task Card → Edit Task**:
   - Trigger: On Click
   - Animation: Smart Animate

#### ทดสอบ Prototype:
1. คลิก Present button (▶) ที่มุมบนขวา
2. เลือก Starting Frame
3. ทดสอบการทำงาน
4. ปรับแก้ตามความเหมาะสม

### ขั้นตอนที่ 9: Responsive Design

เพิ่ม Constraints เพื่อให้ Design ปรับตัวได้:

1. **Header elements**:
   - Menu icon: Left & Top
   - Title: Left & Right (Scale)
   - Profile: Right & Top

2. **Task Cards**:
   - Left & Right (Scale horizontally)
   - Top (Fixed from top)

3. **FAB**:
   - Right & Bottom (Fixed position)

### ขั้นตอนที่ 10: สร้างหน้า Dark Mode (Optional)

1. Duplicate ทุก Frame
2. สร้าง Color Styles สำหรับ Dark Mode:
   - Background: #1F2937
   - Surface: #374151
   - Text: #F9FAFB

3. สลับ Color Styles ใน Dark Mode frames
4. ทดสอบ Contrast และ Readability

---

## Tips และ Best Practices

### 1. การจัดระเบียบไฟล์

#### Page Organization:
```
📄 Cover (Description & Preview)
📄 Design System (Colors, Typography, Components)
📄 Wireframes (Low-fidelity sketches)
📄 Mockups (High-fidelity designs)
📄 Prototype (Interactive flows)
📄 Archive (Old versions)
```

#### Layer Naming:
- ใช้ชื่อที่สื่อความหมาย: "Button/Primary" แทน "Rectangle 1"
- ใช้ slash (/) สำหรับ hierarchy
- ใช้ prefix เมื่อจำเป็น: "icon-", "img-"

### 2. Keyboard Shortcuts ที่ควรรู้

**พื้นฐาน**:
- `Cmd/Ctrl + C`: Copy
- `Cmd/Ctrl + V`: Paste
- `Cmd/Ctrl + D`: Duplicate
- `Cmd/Ctrl + G`: Group
- `Cmd/Ctrl + Shift + G`: Ungroup

**Tools**:
- `V`: Select (Move tool)
- `F`: Frame
- `R`: Rectangle
- `O`: Ellipse
- `T`: Text
- `L`: Line

**View**:
- `Cmd/Ctrl + 0`: Zoom to 100%
- `Cmd/Ctrl + 1`: Zoom to fit
- `Cmd/Ctrl + 2`: Zoom to selection
- `Cmd/Ctrl + Plus/Minus`: Zoom in/out

**Auto Layout**:
- `Shift + A`: Add Auto Layout
- `Alt + drag`: Adjust padding
- `Shift + Alt + drag`: Adjust gap

**Components**:
- `Cmd/Ctrl + Alt + K`: Create Component
- `Cmd/Ctrl + Alt + B`: Detach Instance

### 3. Plugins แนะนำ

**Content Generation**:
- **Unsplash**: รูปภาพฟรีคุณภาพสูง
- **Content Reel**: สร้างข้อมูลจำลอง (Lorem ipsum, names, etc.)
- **Avatars**: สร้าง Avatar ต่างๆ

**Productivity**:
- **Autoflow**: สร้าง User Flow อัตโนมัติ
- **Remove BG**: ลบพื้นหลังรูปภาพ
- **Stark**: ตรวจสอบ Accessibility และ Contrast

**Design System**:
- **Style Organizer**: จัดระเบียบ Styles
- **Design Lint**: ตรวจสอบความสม่ำเสมอ
- **Instance Finder**: ค้นหา Component instances

**Export**:
- **Figma to Code**: แปลง Design เป็น HTML/CSS/React
- **Iconify**: ไอคอนนับพัน
- **PDF Export**: Export เป็น PDF

### 4. Design Handoff

เมื่อเสร็จสิ้นการออกแบบ เตรียมส่งมอบให้ Developer:

1. **ตรวจสอบ Design**:
   - ทุก Text ใช้ Text Styles
   - ทุกสีใช้ Color Styles
   - Spacing สม่ำเสมอ
   - Assets พร้อม Export

2. **เตรียม Assets**:
   - Export icons เป็น SVG
   - Export images ที่ใช้ (1x, 2x, 3x)
   - Export app icon ทุกขนาด

3. **Developer Handoff**:
   - เปิด "Dev Mode" ใน Figma
   - Developer สามารถดู:
     - CSS code
     - Measurements
     - Assets
     - Interactive prototype

4. **Documentation**:
   - สร้าง Style Guide
   - อธิบาย Components และการใช้งาน
   - ระบุ Interactions และ Animations
   - แนบ User Flow diagrams

### 5. Version Control

- ใช้ "Version History" เซฟเวอร์ชันสำคัญ
- ตั้งชื่อเวอร์ชันที่มีความหมาย
- เช่น: "v1.0 - Initial Design", "v1.1 - After User Testing"

### 6. Performance Tips

- ใช้ Components แทนการ Copy-Paste
- เก็บ Images ขนาดพอเหมาะ (ไม่เกิน 4096px)
- ลบ Hidden Layers ที่ไม่ใช้
- ใช้ Flatten เมื่อมี Vector ซับซ้อน

---

## แหล่งเรียนรู้เพิ่มเติม

### Official Resources

- **Figma Help Center**: https://help.figma.com
- **Figma YouTube Channel**: https://www.youtube.com/c/Figmadesign
- **Figma Community**: https://www.figma.com/community
- **Figma Best Practices**: https://www.figma.com/best-practices

### Thai Communities

- **Facebook Groups**:
  - Figma Thailand
  - UI/UX Designer Thailand
  - Designer Thailand

### Courses & Tutorials

- **Figma Official Tutorial**: https://www.figma.com/resources/learn-design/
- **YouTube Channels**:
  - Figma (Official)
  - DesignCourse
  - Flux Academy
  - CharliMarieTV

### Design Inspiration

- **Dribbble**: https://dribbble.com
- **Behance**: https://www.behance.net
- **Mobbin**: https://mobbin.com (Mobile design patterns)
- **Figma Community**: https://www.figma.com/community

### Design Systems Examples

- **Material Design**: https://material.io
- **Apple Human Interface Guidelines**: https://developer.apple.com/design/
- **Ant Design**: https://ant.design
- **Atlassian Design System**: https://atlassian.design

---

## สรุป

การออกแบบ Mobile App ด้วย Figma ประกอบด้วยขั้นตอนหลัก:

1. **วางแผน**: กำหนด User Flow, Features, และ Design System
2. **สร้าง Design System**: Colors, Typography, Components
3. **Wireframe**: ร่าง Layout พื้นฐาน
4. **Mockup**: ออกแบบรายละเอียดทุกหน้า
5. **Prototype**: เชื่อมโยงหน้าจอและทำ Interaction
6. **Test**: ทดสอบกับผู้ใช้และปรับแก้
7. **Handoff**: ส่งมอบให้ Developer

**จำไว้ว่า**:
- Practice makes perfect - ฝึกฝนบ่อยๆ
- เรียนรู้จาก Community และ Designers คนอื่น
- อัพเดทความรู้เสมอ Figma มีฟีเจอร์ใหม่ตลอด
- Focus on user needs ไม่ใช่แค่ความสวยงาม

---

## ติดต่อและข้อเสนอแนะ

หากมีคำถามหรือข้อเสนอแนะเกี่ยวกับคู่มือนี้:
- เปิด Issue ใน GitHub repository นี้
- หรือติดต่อผ่านช่องทางอื่นๆ ที่ระบุไว้

**Happy Designing! 🎨**