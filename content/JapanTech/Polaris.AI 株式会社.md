---
aliases: [NXP AI Expo 2026, MCX Portfolio, Edge AI Demos]
tags: [AI, NXP, Edge, FaceRecognition, LLM ,VLM]
date_created: 2026-04-21
source: 2026年4月パンフレット.pdf
---

# 📝 สรุปไฮไลต์ NXP AI Expo 2026: โซลูชัน Edge AI สำหรับโลกอนาคต
> **TL;DR (Top-Level Summary):**
> NXP นำเสนอพอร์ตโฟลิโอฮาร์ดแวร์ที่หลากหลายที่สุด ตั้งแต่ **MCX MCU** ไปจนถึง **Ara Discrete NPU** โดยเน้นจุดเด่นที่ความสมดุลระหว่าง **ประสิทธิภาพและพลังงาน (Performance & Power)** และการประยุกต์ใช้ AI ในสถานการณ์จริงโดยไม่ต้องพึ่งพาคลาวด์

## 📌 Key Takeaways
* **Domain Isolation:** การแยก Main System และ Subsystem ใน **i.MX RT700** ช่วยให้ AI ทำงานเฉพาะตอนที่จำเป็น ทำให้ประหยัดพลังงานระดับ Ultra-low power
* **Plug & Play AI:** การใช้ **Ara240 NPU** เป็นตัวเร่งความเร็วแบบ外付け (External) ช่วยให้อัปเกรดระบบเดิม (เช่น i.MX หรือ x86) ให้รองรับ LLM ได้ทันที
* **Agentic AI:** การก้าวข้ามจาก ML แบบเดิมไปสู่ระบบ **Autonomous Edge AI** ด้วย eIQ Agentic AI Framework

---

## 📖 รายละเอียดการสาธิต (Technical Demos)

### 🤖 เดโม 1: Face Recognition AI ที่ทำงานเฉพาะเมื่อจำเป็น
* **Hardware:** ใช้ `i.MX RT700 Crossover MCU`
* **Concept:** แยกการทำงานของระบบประมวลผลหลักออกจากหน่วยประมวลผลย่อย (Subsystem)
* **Efficiency:** * เร่งความเร็วด้วย **Neutron NPU** ช่วยลดเวลา Run Mode และเพิ่มเวลา Sleep Mode
    * ประหยัดไฟได้มากกว่าการใช้ Cortex-M เพียงอย่างเดียวถึง **172 เท่า** สำหรับ Vision AI
    * ไม่ต้องใช้ DRAM ภายนอกเพราะมี RAM ในตัวขนาดใหญ่ **7.5 MB**

### 💬 เดโม 2: การอัปเกรดระบบเดิมให้รองรับ LLM (Large Language Model)
* **Hardware:** ใช้ `Ara240` (NPU) คู่กับ Host ต่างๆ (เช่น i.MX หรือ x86)
* **Concept:** แยกส่วนประมวลผลหลัก (Core Processing) และส่วนประมวลผล AI ออกจากกัน
* **Capabilities:** แสดงผลการตอบโต้ของ LLM เป็นข้อความและเสียง (Voice Synthesis) โดยไม่ต้องเปลี่ยนโครงสร้างระบบเดิม

### 👁️ เดโม 3: VLM (Vision Language Model) ขนาดจิ๋วแต่ทรงพลัง
* **Hardware:** ใช้ `i.MX 8M Plus` ผสานกับ `Ara240`
* **Concept:** AI ที่สามารถ **"ดู-เข้าใจ-อธิบาย"** เป็นภาษาญี่ปุ่นได้ในตัวอุปกรณ์เอง (Edge)
* **Application:** เหมาะสำหรับระบบความปลอดภัยหรือการวิเคราะห์ภาพที่ต้องการคำอธิบายเชิงบริบทแบบเรียลไทม์

---

## 🛠️ เครื่องมือพัฒนา (Enablement Tools)
* **eIQ® AI Software:** รองรับโมเดลจาก TensorFlow, PyTorch และ ONNX
* **eIQ GenAI Flow:** เครื่องมือสร้างแอปพลิเคชัน Generative AI ที่มีความรู้เฉพาะทางและมีระบบป้องกันข้อมูล (Data Guardrail)
* **EdgeLock 2GO:** บริการคลาวด์สำหรับจัดการกุญแจรหัส (Key Management) และการอัปเดต OTA ที่ปลอดภัย

## 🔗 Connections & Next Steps
* **Related Notes:** [[Edge AI Hardware]], [[AI Security]], [[Ara240 Technical Specs]]
* **Action Items:**
    * ศึกษาการใช้ **eIQ Time Series Studio** สำหรับงานวิเคราะห์ความผิดปกติของมอเตอร์ (Motor Health Monitoring)
    * ตรวจสอบโปรแกรม **Product Longevity** เพื่อยืนยันระยะเวลาส่งมอบชิ้นส่วน (10-15 ปี) สำหรับโปรเจกต์ระยะยาว