---
aliases: [Spingence, Edgestar, Enterprise AI Platform]
tags: [Infrastructure, Enterprise, Security, DX]
date_created: 2026-04-21
source: Spingence_Edgestar Flyer.pdf
---

# 📝 สรุปข้อมูล Edgestar: แพลตฟอร์มสร้างสภาพแวดล้อม AI สำหรับองค์กร
> **TL;DR (Top-Level Summary):**
> **Edgestar** โดย **Spingence** เป็นแพลตฟอร์มที่ช่วยให้องค์กรสามารถสร้างและปรับแต่งสภาพแวดล้อม AI เฉพาะตัวได้อย่างง่ายดาย โดยเน้นความปลอดภัยสูงสุดด้วยระบบ **ปิด (Closed Environment)** และให้ประสิทธิภาพเทียบเท่าโมเดลระดับโลกอย่าง GPT-5.2 หรือ Sonnet 4.5

## 📌 Key Takeaways
* **High Performance:** รองรับฟังก์ชันการทำงานที่เทียบเท่าโมเดลชั้นนำในปัจจุบันภายในสภาพแวดล้อมของบริษัทเอง
* **Absolute Security:** ทำงานบนระบบเครือข่ายปิด (Private Network) ทำให้ข้อมูลไม่รั่วไหลออกสู่ภายนอก
* **No-Code Customization:** แผนก DX หรือฝ่ายไอทีสามารถสร้างสภาพแวดล้อม AI ได้เองโดยไม่ต้องเขียนโค้ด (No-code)

## 📖 เนื้อหาสรุปเชิงลึก (Detailed Summary)

### 🚀 ฟีเจอร์หลักของ AI (AI Functions)
* **Custom Model:** รองรับการทำ Re-learning (Fine-tuning) เพื่อสร้างโมเดลที่เชี่ยวชาญเฉพาะด้านตามความต้องการของธุรกิจ
* **Scalable Infrastructure:** มีการบูรณาการทั้งฮาร์ดแวร์ (GPU Cluster), ซอฟต์แวร์ และแอปพลิเคชันเข้าด้วยกันเพื่อความเสถียรในการใช้งาน
* **Inference Service:** รองรับเอนจินการประมวลผลที่หลากหลาย เช่น vLLM, SGLang และ NVIDIA NIM

### 🛡️ ความปลอดภัยและการจัดการ (Security & Governance)
* **Data Privacy:** ป้องกันข้อมูลรั่วไหลด้วยการทำงานในระบบปิด 100% เหมาะสำหรับองค์กรที่เคร่งครัดเรื่องความปลอดภัยข้อมูล
* **Edgestar Manager:** ระบบบริหารจัดการส่วนกลางที่ช่วยให้เห็นภาพรวมการใช้งาน (Usage Visibility) และจัดการทรัพยากร (Resource Governance) ได้อย่างมีประสิทธิภาพ
* **Security Monitoring:** มีระบบเฝ้าระวังความปลอดภัยที่ช่วยให้ฝ่ายสารสนเทศ (IT Department) มั่นใจในการดำเนินงาน

### 🦾 สถาปัตยกรรมระบบ (System Architecture)
* **Application Layer:** รองรับ Enterprise RAG, AI Assistant และ Department AI Agent
* **Infrastructure Foundation:** ใช้ระบบจัดเก็บข้อมูลแบบกระจายตัว (Distributed File System) และเครือข่ายความเร็วสูง (High-Speed Ethernet) เพื่อรองรับการประมวลผลหนักๆ

## 🔗 Connections & Next Steps
* **Related Notes:** [[RAG SYSTEM]], [[Local LLM]], [[GPU Architecture]]
* **Action Items:**
    * ประเมินความต้องการในการทำ **Specific Domain Model** เพื่อลดการพึ่งพาโมเดลสาธารณะ
    * ตรวจสอบความพร้อมของโครงสร้างพื้นฐานไอทีเพื่อรองรับการติดตั้ง **GPU Cluster** ภายในองค์กร