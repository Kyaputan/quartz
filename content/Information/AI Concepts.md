---
tags:
  - AI
  - DataScience
  - MachineLearning
  - DeepLearning
Created: 2026-04-21
---

# 🧠 Core AI Concepts: From Foundations to Agents

> [!info] 🧭 การจัดกลุ่มความรู้
> AI คือร่มใหญ่ (Umbrella Term) ที่ครอบคลุมหลายศาสตร์ โดยมีลำดับชั้นความซับซ้อนดังนี้ค่ะ

---

## ## 1. The Hierarchy of AI
ความสัมพันธ์ของเทคโนโลยีที่มักถูกสับสน:
- **Artificial Intelligence (AI)**: ศาสตร์ที่ทำให้เครื่องจักรเลียนแบบสติปัญญาของมนุษย์
- **Machine Learning (ML)**: ซับเซตของ AI ที่เน้นให้คอมพิวเตอร์ "เรียนรู้จากข้อมูล" โดยไม่ต้องเขียนโปรแกรมสั่งทุกอย่าง
- **Deep Learning (DL)**: ซับเซตของ ML ที่ใช้โครงข่ายประสาทเทียมหลายชั้น (Neural Networks) เลียนแบบสมองมนุษย์
- **Generative AI (GenAI)**: AI ที่มีความสามารถในการ "สร้าง" ข้อมูลใหม่ (Text, Image, Code)



---

## ## 2. Modern AI Architectures (2026 Edition)
แนวคิดทางสถาปัตยกรรมที่สำคัญที่สุดในปัจจุบัน:
- **Transformer Architecture**: หัวใจของ LLM (Large Language Models) ที่ใช้กลไก "Self-Attention" เพื่อเข้าใจบริบทของข้อมูล
- **Multimodal AI**: ความสามารถในการประมวลผลข้อมูลหลายรูปแบบพร้อมกัน (เช่น ดูภาพ ฟังเสียง และอ่านข้อความไปพร้อมๆ กัน)
- **World Models**: AI ที่เข้าใจกฎฟิสิกส์และความสัมพันธ์ในโลกความเป็นจริง ไม่ใช่แค่เดาคำถัดไป
- **Neuro-Symbolic AI**: การรวมพลังของ Neural Network (เดาเก่ง) เข้ากับ Symbolic Logic (ใช้เหตุผลและกฎเกณฑ์แม่นยำ)

---

## ## 3. Retrieval & Reasoning Techniques
วิธีที่ทำให้ AI ฉลาดและลดการ "มโน" (Hallucination):
- **RAG 2.0 (Retrieval Augmented Generation)**: การให้ AI ไปค้นข้อมูลจากฐานข้อมูลภายนอก (เช่น ไฟล์งานของคุณกัปตัน) ก่อนตอบ
- **Chain-of-Thought (CoT)**: เทคนิคการให้ AI ค่อยๆ คิดทีละ Step เพื่อแก้ปัญหาที่ซับซ้อน
- **Context Engineering**: การออกแบบบริบทและข้อมูลรอบด้านเพื่อให้ AI เข้าใจเจตนาที่แท้จริง

---

## ## 4. The Shift to "Agentic AI"
เปลี่ยนจาก AI ที่ "คุย" เป็น AI ที่ "ทำ":
- **Autonomous Agents**: AI ที่วางแผนเองและใช้เครื่องมือภายนอก (Tools) ได้
- **Model Context Protocol (MCP)**: มาตรฐานใหม่ในปี 2026 ที่ช่วยให้ AI เชื่อมต่อกับ Local Data และเครื่องมือต่างๆ ได้ง่ายขึ้น
- **Small Language Models (SLMs)**: โมเดลขนาดเล็กที่เก่งเฉพาะทาง รันบนอุปกรณ์ [[Edge AI Hardware]] ได้โดยไม่ต้องง้อ Cloud

> [!tip] Integration Idea
> คุณกัปตันสามารถใช้ **Small Language Models** ร่วมกับ [[PLC]] เพื่อตรวจจับความผิดปกติของเครื่องจักรในโรงงาน (Anomaly Detection) ได้แบบ Real-time เลยค่ะ!

---

## ## ⚖️ Ethical & Safety Concepts
- **Explainable AI (XAI)**: การทำให้เราเข้าใจว่า AI ตัดสินใจแบบนั้นเพราะอะไร
- **AI Sovereignty**: แนวคิดที่องค์กรต้องการมี AI และข้อมูลเป็นของตัวเอง (On-premises)
- **Guardrails**: ระบบความปลอดภัยที่คอยสกัดไม่ให้ AI ตอบข้อมูลที่ผิดหรืออันตราย

---
## 🔗 Connections
- [[AI Agent]]
- [[3D Technology]]
- [[Neural Networks]]
- [[Data Engineering]]