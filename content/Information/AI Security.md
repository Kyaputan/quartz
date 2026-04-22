---
tags:
  - AI
  - Security
  - Cybersecurity
  - ThreatIntelligence
Created: 2026-04-21
Status: 🛡️ High Priority
---

# 🛡️ AI Security: Defending the Intelligence

> [!danger] The 2026 Landscape
> การโจมตีด้วย AI (AI-powered attacks) มีความเร็วและแม่นยำสูงขึ้นมาก เช่น การใช้ **AGI-like Agents** ในการสแกนหาช่องโหว่เครือข่ายแบบอัตโนมัติ 24/7 ค่ะ

---

## ## 1. Top 3 AI Vulnerabilities (OWASP LLM 2026)
ช่องโหว่ที่พบบ่อยที่สุดในระบบ AI และ Large Language Models:
1. **Prompt Injection**: การหลอกล่อให้ AI ทำงานนอกเหนือคำสั่ง (เช่น สั่งให้คายข้อมูลความลับบริษัทออกมาระหว่างคุย)
2. **Training Data Poisoning**: การแอบใส่ข้อมูลที่บิดเบือนเข้าไปในชุดข้อมูลที่ใช้เทรน AI เพื่อให้ AI ตัดสินใจผิดพลาดอย่างเป็นระบบ
3. **Insecure Output Handling**: การที่ระบบรับคำตอบจาก AI ไปประมวลผลต่อ (เช่น รันคำสั่ง SQL หรือ Script) โดยไม่มีการตรวจสอบ จนทำให้เกิดการเจาะระบบ



---

## ## 2. Adversarial AI Attacks
การโจมตีที่มุ่งเน้นไปที่ตัว "โมเดล" โดยตรง:
- **Evasion Attacks**: การปรับแต่งข้อมูลเพียงเล็กน้อยที่ตาคนมองไม่เห็น (เช่น Noise บนรูปภาพ) แต่ทำให้ AI แยกแยะผิด (เช่น เห็นป้ายหยุดเป็นป้ายไปต่อ)
- **Model Extraction**: การยิงคำถามซ้ำๆ เพื่อ "แกะรอย" จนสามารถสร้างโมเดลเลียนแบบที่มีประสิทธิภาพใกล้เคียงกันได้ (ขโมยทรัพย์สินทางปัญญา)
- **Membership Inference**: การสืบทราบว่าข้อมูลชุดไหนถูกใช้เทรน AI หรือไม่ เพื่อเจาะข้อมูลส่วนบุคคล

---

## ## 3. Defensive Strategies (The Shield)
แนวทางการป้องกันระบบ AI ให้ปลอดภัย:
- **AI Red Teaming**: การจ้างทีม Expert (หรือใช้ AI Agent) มาจำลองการโจมตีระบบ AI ของตัวเองเพื่อหาช่องโหว่ก่อนแฮกเกอร์
- **Guardrails Implementation**: การวางระบบ "ตะแกรงกรอง" ทั้งขาเข้า (Input Filter) และขาออก (Output Scrubber)
- **Adversarial Training**: การสอน AI ด้วยข้อมูลที่ถูกโจมตีเพื่อให้โมเดลมีความทนทาน (Robustness) มากขึ้น
- **Human-in-the-loop**: การมีจุดตรวจสอบโดยมนุษย์ในขั้นตอนที่มีความเสี่ยงสูง

---

## ## 📜 Standards & Regulations
การทำ AI Security ต้องสอดคล้องกับมาตรฐานเหล่านี้:
- **EU AI Act (August 2026)**: กฎหมายบังคับใช้เต็มรูปแบบที่กำหนดให้ระบบ High-risk AI ต้องมีการรักษาความปลอดภัยไซเบอร์ในระดับสูง
- **NIST AI RMF 1.1**: กรอบการจัดการความเสี่ยงด้าน AI จากสหรัฐฯ
- **ISO/IEC 42001**: มาตรฐานการบริหารจัดการระบบ AI ที่เน้นเรื่อง Security & Trustworthiness

> [!tip] Captain's Perspective
> ในฐานะที่คุณกัปตันดูแลระบบ [[Network]] และ [[PLC]] การทำ **AI Security** ควรเน้นไปที่ **Network Segmentation** เพื่อไม่ให้ AI Agent ที่อาจถูกควบคุมโดยแฮกเกอร์สามารถเข้าถึงส่วนควบคุมเครื่องจักรได้โดยตรงค่ะ

---
## 🔗 Connections
- [[AI Agent]]
- [[AI Quality Assurance Standards]]
- [[Cybersecurity]]
- [[Data Privacy in AI]]