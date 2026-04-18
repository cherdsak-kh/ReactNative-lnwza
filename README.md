<div align="center">
  <h1 align="center">📱 ReactNative-lnwza</h1>
  <p align="center">
    <strong>แอปพลิเคชันมือถือที่รวบรวมฟังก์ชันการใช้งานหลากหลาย พัฒนาด้วย React Native และ Expo</strong>
  </p>
  <p align="center">
    <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native" />
    <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" alt="Expo" />
    <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
    <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase" />
  </p>
</div>

<br />

## 📖 เกี่ยวกับโปรเจกต์ (About The Project)

โปรเจกต์นี้เป็นแอปพลิเคชันมือถือที่พัฒนาเพื่อแสดงศักยภาพของการใช้ **React Native** ร่วมกับ **Expo Framework** โดยมีการประยุกต์ใช้แพ็กเกจและฟีเจอร์สำคัญๆ อย่างครบครันในแอปเดียว มีระบบการนำทางที่ทันสมัยด้วย **Expo Router** และการจัดการข้อมูลแบบเรียลไทม์ควบคู่กับฐานข้อมูลบนคลาวด์ 

เหมาะสำหรับการใช้เป็นกรณีศึกษาหรือเป็นโครงสร้างเริ่มต้นสำหรับโปรเจกต์ที่ต้องการฟังก์ชันที่หลากหลาย และครอบคลุมการใช้งานเครื่องมือในสมาร์ตโฟน (Hardware APIs) อย่างเต็มที่

### 🌟 ฟีเจอร์หลัก (Key Features)

- 🔐 **ระบบรหัสยืนยันตัวตน (Authentication):** จัดการ Session และการล็อกอินเข้าสู่ระบบด้วย Supabase
- 📚 **จัดการสมุดบันทึก (Book Management):** รวบรวมข้อมูลหนังสือ และรองรับทั้งการจัดเก็บภายในเครื่องและการจัดการแบบออนไลน์ (Online/Offline Storage)
- 🏋️‍♂️ **เครื่องมือด้านสุขภาพและออกกำลังกาย (Health & Exercise):** ฟีเจอร์สำหรับการคำนวณและแสดงค่า BMI การบันทึกและติดตามการออกกำลังกายพร้อมแสดงผล **สถิติผ่านกราฟเชิงลึกทางสถิติ** (ด้วย `react-native-chart-kit`)
- 🗺️ **บริการตำแหน่งที่ตั้ง (Location Services):** การระบุพิกัด GPS, การแสดงแผนที่ (ด้วย `react-native-maps`) และฟังก์ชัน **Location Quiz** ที่ใช้ระบุตำแหน่งตอบคำถามสถานที่น่าสนใจ
- 📝 **จัดการรายการสิ่งที่ต้องทำ (To-Do List):** จดบันทึกและติดตามงานที่ต้องทำในแต่ละวัน
- 🎮 **เชื่อมต่อและเรียนรู้ API (Pokemon Data):** ข้อมูลตัวอย่างจากการดึงข้อมูลและนำเสนอข้อมูลโปเกมอนจากภายนอก
- 💾 **การเชื่อมต่อ Backend (Supabase):** เป็นศูนย์กลางในการจัดการข้อมูลทั้งหมดผ่าน Cloud database แบบ Real-time
- ⚡ **Local Storage:** จัดเก็บข้อมูลแบบชั่วคราวและถาวรในเครื่องด้วย Async Storage

---

## 🛠 เทคโนโลยีที่ใช้งาน (Built With)

* **ภาพรวมและจัดการ UI:** [React Native](https://reactnative.dev/), [Expo](https://expo.dev/)
* **การนำทาง (Routing):** [Expo Router](https://docs.expo.dev/router/introduction/)
* **การจัดการและเก็บรักษาข้อมูล (Backend & Storage):** [Supabase](https://supabase.com/), `@react-native-async-storage/async-storage`
* **ระบบแผนที่และเซนเซอร์:** `react-native-maps`, `expo-location`
* **นำเสนอภาพรวมข้อมูล (Data Visualization):** `react-native-chart-kit`

---

## 🚀 การเริ่มต้นใช้งาน (Getting Started)

คำแนะนำเหล่านี้จะช่วยให้คุณสามารถรันโปรเจกต์นี้ในสภาพแวดล้อมจำลอง (Local Environment) เพื่อการพัฒนาและทดสอบได้

### ข้อกำหนดเบื้องต้น (Prerequisites)

- ติดตั้ง **Node.js**: [Download](https://nodejs.org/) (แนะนำเวอร์ชัน LTS)
- แฟลตฟอร์มจำลอง: **Android Studio** (สำหรับ Android Emulator) หรือ **Xcode** (สำหรับ iOS Simulator) หรือจะใช้วิธีรันแอปบนเครื่องจริงผ่านแอปพลิเคชัน Expo Go

### วิธีการติดตั้ง (Installation)

1. **โคลนหรือเข้าถึงโฟลเดอร์โปรเจกต์ และทำการติดตั้งแพ็กเกจ (Dependencies):**
   เปิดโปรแกรม Terminal หรือ Command Prompt เข้าไปยังโฟลเดอร์หลักของโปรเจกต์ และรันคำสั่งต่อไปนี้:
   ```bash
   npm install
   ```

2. **ตั้งค่าฐานข้อมูล Supabase:**
   (ขณะนี้ในระบบมีการกำหนดค่าเชื่อมต่อ Config ไว้แล้วในฟังก์ชันส่วนลึกของแอปพลิเคชัน คุณสามารถตรวจสอบและปรับแต่งการตั้งค่า URL และ API Key ได้ที่ไฟล์ `utils/supabase.ts`)

3. **รันเซิร์ฟเวอร์ทำงาน (Start the Development Server):**
   ```bash
   npm start
   ```

4. **เปิดใช้งานแอปพลิเคชัน:**
   เมื่อรันเซิร์ฟเวอร์แล้ว จะมีเมนูตัวเลือกใน Terminal หรือหน้าต่างแยกบนเบราว์เซอร์:
   * กด `a` หากต้องการรันเพื่อเปิดแอปใน Android Emulator 
   * กด `i` หากต้องการรันเพื่อเปิดแอปใน iOS Simulator
   * หรือคุณสามารถใช้งานสมาร์ตโฟนที่มีแอปพลิเคชัน **Expo Go** สแกน QR Code ที่แสดงขึ้นเพื่อทดลองใช้งานบนเครื่องจริงได้ทันที 📱

---

## 🧪 การทดสอบและตรวจสอบมาตรฐานการเขียนโค้ด (Linting)

รันคำสั่งตรวจสอบรูปแบบ Syntax errors และ Coding Style ผ่านระบบ ESLint เพื่อความเรียบร้อยของโค้ด:
```bash
npm run lint
```

---

## 📂 โครงสร้างโปรเจกต์หลัก (Project Structure)

```text
ReactNative-lnwza/
├── app/               # การใช้ Expo Router ไฟล์หน้าจอหลักอยู่ที่นี่
│   ├── (auth)/        # Route Group: หน้าเข้าระบบ (Login/Register)
│   ├── (tabs)/        # Route Group: เมนูด้านล่าง (Bottom Tabs Navigation)
│   ├── (pokemon)/     # Route Group: ข้อมูลโปเกมอน
│   ├── (exercise)/    # Route Group: การออกกำลังกายและสุขภาพ
│   ├── book/          # หน้าฟังก์ชันระบบจัดการหนังสือ
│   ├── *              # หน้าอื่นๆ เช่น กราฟแสดงสถิติ, แผนที่นำทาง, หน้าเพิ่ม Todo ฯลฯ
├── assets/            # พื้นที่จัดเก็บไฟล์ภายนอกอาทิ รูปภาพประจำเครื่อง หรือ Fonts
├── components/        # ส่วนแสดงผล UI Component ย่อยๆ
├── utils/             # กลุ่มฟังก์ชัน Service ต่างๆ (Supabase Client, API Fetchers, Local Storage)
├── package.json       # ไฟล์ระบุแพ็กเกจที่ติดตั้งไว้ทั้งหมดในโปรเจกต์
└── app.json           # การตั้งค่าต่างๆ (Config) ของแอปสำหรับฝั่งขององค์ประกอบ Expo
```

---

## 📦 การนำไปใช้งานจริง (Deployment)

เมื่อพัฒนาและทดสอบแอปพลิเคชันสำเร็จ คุณสามารถนำไประเบเบิลด์เป็นไฟล์การติดตั้งอย่าง `.apk` หรือ `.aab` สำหรับ Android หรือทดลองฝั่ง iOS ได้ ผ่านระบบ **Expo Application Services (EAS)** 

อ่านคู่มือเพิ่มเติมเกี่ยวกับขั้นตอนเหล่านี้ได้อย่างละเอียดที่: [EAS Build Introduction](https://docs.expo.dev/build/introduction/)

---

## 🤝 การมีส่วนร่วม (Contributing)

สามารถส่ง Pull Requests มาได้เลยหากต้องการพัฒนาฟีเจอร์เพิ่มเติม หรืออ่านข้อตกลงแนวทางในไฟล์ `CONTRIBUTING.md` หากทางทีมมีการระบุไว้

---

## 📄 ลิขสิทธิ์ (License)

โปรเจกต์นี้สงวนสิทธิ์อยู่ภายใต้ **MIT License** อนุญาตให้นำไปพัฒนาต่อยอด หรือเพื่อการศึกษา - ศึกษาข้อมูลเพิ่มเติมที่ไฟล์ `LICENSE.md`
