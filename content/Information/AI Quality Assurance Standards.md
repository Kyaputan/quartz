---
tags:
  - AI
  - QualityAssurance
  - Standards
  - Compliance
  - ISO42001
Created: 2026-04-21
Status: 🛡️ Standardized
---

# 🛡️ AI Quality Assurance Standards (2026 Edition)

> [!warning] Critical Update
> ตั้งแต่วันที่ **2 สิงหาคม 2026** เป็นต้นไป **EU AI Act** จะมีผลบังคับใช้อย่างเต็มรูปแบบ ซึ่งกำหนดมาตรฐานขั้นต่ำสำหรับระบบ AI ที่มีความเสี่ยงสูง (High-Risk AI) ทั่วโลกค่ะ

---

## ## 1. ISO/IEC 42001:2023 (AI Management System)
นี่คือ "พระเอก" ของงาน QA ในปัจจุบัน เป็นมาตรฐานสากลตัวแรกที่เน้นการบริหารจัดการ AI ทั้งองค์กร:
- **Risk Management**: การประเมินความเสี่ยงตลอด Life Cycle ของ AI
- **Data Governance**: มาตรฐานการคัดเลือกและจัดการข้อมูลเพื่อเทรนโมเดล
- **Ethical Impact**: การประเมินผลกระทบด้านจริยธรรมและสังคม
- **Continuous Monitoring**: ระบบการตรวจสอบประสิทธิภาพหลังการติดตั้ง (Post-deployment)



---

## ## 2. EU AI Act Compliance
กฎหมายที่มีผลกระทบกว้างที่สุด (Extra-territorial effect) แม้อยู่ไทยถ้าบริการใน EU ก็ต้องทำค่ะ:
- **Quality Management System (QMS)**: ข้อบังคับตาม Article 17 สำหรับระบบ High-risk
- **Accuracy, Robustness & Cybersecurity**: ต้องระบุระดับความแม่นยำและความทนทานต่อการโจมตี (เช่น Adversarial Attacks)
- **Human Oversight**: การออกแบบให้มนุษย์สามารถเข้าแทรกแซงหรือหยุดการทำงานของ AI ได้ตลอดเวลา
- **Transparency & Logging**: การเก็บ Log การตัดสินใจของ AI ย้อนหลังอย่างน้อย 6-12 เดือน

---

## ## 3. NIST AI Risk Management Framework (AI RMF 1.1)
มาตรฐานจากฝั่งสหรัฐฯ ที่นิยมใช้เป็นแนวทางปฏิบัติ (Best Practices):
- **Govern**: วางโครงสร้างวัฒนธรรมการจัดการความเสี่ยง
- **Map**: ระบุความสัมพันธ์ระหว่าง AI และบริบทที่นำไปใช้
- **Measure**: การวัดผลเชิงคุณภาพและปริมาณ (เช่น Bias Detection)
- **Manage**: การตอบสนองต่อความเสี่ยงที่เกิดขึ้นจริง

---

## ## 4. Technical QA Metrics (The "Checklist")
ในการทำ QA ทางเทคนิค คุณกัปตันควรตรวจสอบหัวข้อเหล่านี้:
1. **Bias & Fairness**: ใช้เครื่องมือตรวจสอบว่าโมเดลไม่เอนเอียงตามเพศ อายุ หรือเชื้อชาติ
2. **Explainability (XAI)**: สามารถอธิบายได้ว่าทำไม AI ถึงให้คำตอบนั้น (เช่น ใช้ SHAP หรือ LIME)
3. **Data Integrity**: ตรวจสอบว่าข้อมูลไม่มีการปนเปื้อน (Data Poisoning)
4. **Performance Drift**: ติดตามว่าโมเดลเก่งน้อยลงตามกาลเวลาหรือไม่

---

## ## 🛠️ AI QA Tools for 2026
- **Giskard**: Open-source framework สำหรับการทำ Testing & Debugging ML Models
- **Evidently AI**: ตรวจสอบ Data Drift และ Model Performance
- **PyCaret (QA modules)**: ช่วยทำ Low-code validation
- **IBM AI Fairness 360**: ชุดเครื่องมือตรวจจับและลดความเหลื่อมล้ำในโมเดล

> [!tip] Captain's Perspective
> สำหรับงานด้าน [[PLC]] และ [[Network]] มาตรฐาน **ISO/IEC 42001** จะเป็นตัวช่วยยืนยันว่าระบบ AI ที่คุณกัปตันเอามาคุมเครื่องจักรนั้นมี "Reliability" สูงพอที่จะไม่ทำให้เกิดอุบัติเหตุในโรงงานค่ะ

---
## 🔗 Connections
- [[AI Concepts]]
- [[AI Agent]]
- [[Data Privacy in AI]]