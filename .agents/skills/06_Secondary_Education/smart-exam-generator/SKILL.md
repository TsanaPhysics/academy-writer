---
name: smart-exam-generator
description: สร้างข้อสอบ (MCQ/Descriptive) พร้อมเฉลยละเอียดและเกณฑ์การให้คะแนน (Rubric) ที่วัดผลได้จริง
---

# Smart Exam Generator

ทักษะในการสร้างเครื่องมือวัดผลการเรียนรู้ที่แม่นยำ รวดเร็ว และครอบคลุมทักษะการคิดหลายระดับ

## Workflow
1. **Table of Specifications (TOS)**: กำหนดสัดส่วนข้อสอบตามเนื้อหาและระดับพฤติกรรม (Bloom's Taxonomy)
2. **Item Drafting**:
   - **MCQ**: สร้างข้อสอบปรนัยพร้อมตัวเลือกลวงที่มีคุณภาพ
   - **Descriptive**: สร้างข้อสอบอัตนัยที่เน้นการวิเคราะห์และประยุกต์ใช้
3. **Answer Key & Explanation**: จัดทำเฉลยละเอียดที่อธิบายเหตุผลของคำตอบที่ถูกต้อง
4. **Rubric Design**: สร้างเกณฑ์การให้คะแนน (Scoring Rubric) ที่ชัดเจนสำหรับข้อสอบอัตนัยหรือชิ้นงาน

## Triggers
- "ออกข้อสอบบทที่ [เลขบท] จำนวน [จำนวน] ข้อ"
- "สร้างเกณฑ์การให้คะแนนสำหรับงานเขียนเรียงความ"
- "ช่วยวิเคราะห์ความยากง่ายของข้อสอบชุดนี้"

## Core Capabilities
- Multi-level question generation (Recall to Evaluation).
- Distractor (ตัวลวง) analysis and optimization.
- Rubric and criteria-based assessment design.

## Implementation Principles
- **Validity & Reliability**: ข้อสอบต้องวัดในสิ่งที่ต้องการวัดและมีความเที่ยงตรง
- **Clarity**: คำถามต้องชัดเจน ไม่กำกวม
- **Constructive Feedback**: เฉลยต้องช่วยให้นักเรียนเข้าใจจุดที่ผิดและเรียนรู้เพิ่มได้
