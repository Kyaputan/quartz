---
aliases: [Jitera Development, Jitera AI Agent, AI-Driven Development]
tags: [Software-Engineering, Agent, DX, status , review]
date_created: 2026-04-21
source: [Jitera_gyomuAI.pdf, Jitera_kaihatsuAI.pdf]
---

# 📝 สรุปแพลตฟอร์มการพัฒนาและเอเยนต์ AI โดย Jitera
> **TL;DR (Top-Level Summary):**
> Jitera มุ่งเน้นการปฏิวัติวงการซอฟต์แวร์ด้วยการทำ `AI-Driven Development` ที่ช่วยให้สร้างระบบได้เร็วขึ้นสูงสุดถึง 10 เท่า โดยใช้กลยุทธ์ "การพัฒนาแบบบล็อกไม้" (`Tsumiki Development`) ควบคู่กับ `AI Agent` ที่ช่วยปิดงานจิปาถะในออฟฟิศให้เสร็จสิ้นโดยอัตโนมัติ

## 📌 Key Takeaways
* **10x Faster Development:** ใช้ AI ช่วยเขียนโค้ดและสร้างระบบจากความต้องการ (Requirements) ทำให้ลดระยะเวลาพัฒนาลงได้อย่างมหาศาล
* **Tsumiki (Building Blocks) Strategy:** ลดการเขียนโค้ดซ้ำซ้อนในฟีเจอร์พื้นฐานได้ถึง 80% โดยนำโมดูลสำเร็จรูปมาประกอบกันเหมือนบล็อกไม้
* **Seamless AI Collaboration:** ตั้งแต่การออกแบบใน `Figma` ไปจนถึงการเขียนโค้ดอัตโนมัติโดย `Devin AI` ทำให้การทำงานระหว่างคนและ AI ไร้รอยต่อ

---

## 📖 เนื้อหาสรุปเชิงลึก (Detailed Summary)

### 💻 Jitera Kaihatsu: การพัฒนาซอฟต์แวร์ที่ขับเคลื่อนด้วย AI
Jitera เปลี่ยนวิธีการทำ Scratch Development ที่เชื่องช้าให้กลายเป็นระบบที่มีประสิทธิภาพสูง:
* **AI-Driven Practice:** นำ Generative AI มาใช้ในทุกขั้นตอน ตั้งแต่การทำสรุปการประชุม, การร่าง `Requirements Definition`, ไปจนถึงการสร้าง `Test Case` อัตโนมัติ [cite: 3475, 3481-3483]
* **Tsumiki Development:** พัฒนาส่วนประกอบ (Components) ที่ใช้บ่อยไว้เป็นโมดูล เช่น ระบบจัดการผู้ใช้, ระบบล็อกอิน หรือการจัดการไฟล์ เพื่อให้วิศวกรโฟกัสเฉพาะ "ตรรกะทางธุรกิจที่เฉพาะตัว" (Business Logic) เท่านั้น
* **Prototyping Speed:** สามารถเปลี่ยน `Design File` จาก Figma ให้กลายเป็นโค้ด Frontend ได้ทันที ช่วยลดข้อผิดพลาดในการสื่อสารระหว่าง Designer และ Developer

### 🤖 Jitera Gyomu AI: เอเยนต์จบงานเพื่อองค์กร
โซลูชันนี้เน้นการนำ AI มาใช้ในงานบริหารจัดการทั่วไปเพื่อเพิ่ม Productivity:
* **Autonomous Planning:** AI Agent ไม่ได้แค่ตอบคำถาม แต่สามารถ "วางแผน" สเต็ปการทำงานและเรียกใช้เครื่องมือต่าง ๆ (เช่น Web Search, File Operation) เพื่อให้งานสำเร็จ
* **Multi-Model Intelligence:** ระบบจะเลือกใช้ Model ที่เหมาะสมที่สุดอัตโนมัติ (เช่น GPT สำหรับงานทั่วไป หรือ Gemini สำหรับงานที่ต้องอ่านภาพ) เพื่อประสิทธิภาพสูงสุดในต้นทุนที่ต่ำที่สุด
* **Integration & Security:** เชื่อมต่อกับ `SharePoint` และ `Google Drive` ภายใต้สภาพแวดล้อมที่ปลอดภัย (Security-first) ทำให้ AI สามารถใช้ข้อมูลจริงของบริษัทมาตอบคำถามหรือสร้างเอกสารได้

---

## 🔗 Connections & Next Steps
* **Related Notes:** [[AI Software Engineering]], [[Component-Based Architecture]], [[AI Agent]]
* **Action Items:**
    * [ ] พิจารณาใช้ Jitera ในโปรเจกต์ที่ต้องการ `Fast Prototyping` เพื่อทดสอบตลาดก่อนลงทุนเต็มตัว
    * [ ] ศึกษาแนวทางการสร้าง `Custom RAG` ร่วมกับ Jitera AI Agent เพื่อใช้เป็นฐานความรู้ภายในทีม