---
tags:
  - AnomalyDetection
  - AI
  - MachineLearning
  - Industry4.0
  - PredictiveMaintenance
Created: 2026-04-21
Category: DataScience_Industrial
---

# 🔍 Anomaly Detection: The Ghost in the Data

> [!abstract] Overview
> **Anomaly Detection** คือกระบวนการระบุข้อมูลที่มีรูปแบบเบี่ยงเบนไปจาก "ความปกติ" (Baseline) อย่างมีนัยสำคัญ ในปี 2026 เราก้าวข้ามระบบ Threshold-based ไปสู่ **Self-learning Systems** ที่เข้าใจบริบทของงานค่ะ

---

## ## 1. Types of Anomalies (ประเภทความผิดปกติ)
1. **Point Anomalies**: ข้อมูลจุดเดียวที่กระโดดออกจากกลุ่ม (เช่น ยอดใช้ไฟฟ้าพุ่งสูงผิดปกติในวินาทีเดียว)
2. **Contextual Anomalies**: ผิดปกติ "ตามบริบท" (เช่น มอเตอร์ร้อน 80°C ปกติถ้าเครื่องรัน 100% แต่จะผิดปกติมากถ้าเครื่องกำลัง Idle)
3. **Collective Anomalies**: ข้อมูลชุดหนึ่งที่ดูปกติถ้ามองแยกกัน แต่เมื่อรวมกันแล้วผิดปกติ (เช่น สัญญาณ Sensor หลายตัวค่อยๆ Drift ไปในทิศทางที่บ่งบอกว่าตลับลูกปืนกำลังจะแตก)

---

## ## 🧠 2. Modern Techniques 2026
การเลือกใช้อัลกอริทึมให้เหมาะกับข้อมูล:

### A. Statistical Methods (พื้นฐานแต่ทรงพลัง)
- **Z-Score / Standard Deviation**: เหมาะกับข้อมูลที่มีการกระจายตัวแบบปกติ (Normal Distribution)
- **IQR (Interquartile Range)**: ใช้ตรวจจับ Outliers ในข้อมูลที่ไม่เป็นระเบียบมากนัก

### B. Machine Learning (Unsupervised)
- **Isolation Forest**: อัลกอริทึมยอดนิยมในปี 2026 ที่ใช้หลักการ "แยกข้อมูลที่ผิดปกติออกได้ง่ายกว่าข้อมูลปกติ" (เพราะข้อมูลผิดปกติมีน้อยและแตกต่าง)
- **Local Outlier Factor (LOF)**: วัดความหนาแน่นของข้อมูลรอบๆ จุดนั้นๆ
- **One-Class SVM**: ฝึกสอนเฉพาะข้อมูล "ปกติ" เพื่อให้ระบบรู้ว่าอะไรที่ไม่ใช่พวกของมัน

### C. Deep Learning (High-Performance)
- **Autoencoders**: AI ที่เรียนรู้การบีบอัดและคลายข้อมูลปกติ หากเจอข้อมูลผิดปกติ AI จะคลายข้อมูลออกมาได้ไม่เหมือนเดิม (Reconstruction Error สูง)
- **LSTM-AD**: เหมาะสำหรับข้อมูล Time-series จาก [[IoT]] ที่มีความต่อเนื่องทางเวลา

---

## ## 🏭 Industrial Use Cases (PLC & IoT)
- **Predictive Maintenance**: ตรวจจับความสั่นสะเทือน (Vibration) หรือความร้อนที่เพิ่มขึ้นทีละนิดก่อนเครื่องจักรจะพัง
- **Quality Assurance**: ใช้ AI Vision ตรวจสอบพื้นผิวชิ้นงานหาตำหนิที่กฎ (Rule-based) ทั่วไปตรวจไม่เจอ
- **Cybersecurity**: ตรวจสอบ [[Network_Traffic]] ในวง [[PLC]] เพื่อหาการบุกรุกหรือคำสั่งที่ผิดปกติ
- **Energy Optimization**: ตรวจจับการรั่วไหลของลมอัด (Compressed Air) หรือพลังงานในระบบ

---

## ## 🛠️ Tools & Platforms 2026
| Tool | Strength | Best For |
| :--- | :--- | :--- |
| **MATLAB R2026a** | Native Anomaly Detection Apps | วิศวกรสายคณิตศาสตร์/วิจัย |
| **MachineCDN** | PLC-to-AI Pipeline (3-min setup) | งานโรงงานที่ต้องการความเร็ว |
| **Fabrico** | Context-aware Monitoring | เชื่อม Machine State เข้ากับ Sensor |
| **Datadog / Dynatrace** | IT Infrastructure Monitoring | งานสาย Network & Server |

> [!tip] Captain's Strategy
> "The Drift is the Danger" — ในงาน [[PLC]] อย่ารอให้ Alarm ดังค่ะ ให้ใช้ AI Monitor **Cycle Time** ถ้าเครื่องทำงานช้าลงเพียง 0.2 วินาทีอย่างต่อเนื่อง นั่นคือสัญญาณแรกของความผิดปกติเชิงกล (Mechanical Anomaly) ค่ะ

---
## 🔗 Connections
- [[AI Agent]]
- [[AMR]]
- [[AI Quality Assurance Standards]]
- [[Smart Factory]]
- [[Computer Vision]]