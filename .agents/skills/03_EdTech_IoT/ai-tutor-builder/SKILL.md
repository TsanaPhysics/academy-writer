---
name: ai-tutor-builder
description: ผสานรวม LLMs (GPT-4o) เพื่อสร้างระบบแชทบอทติวเตอร์อัจฉริยะที่ตอบโต้ตามเนื้อหาบทเรียนและวิเคราะห์จุดอ่อนรายบุคคล
---

# AI Tutor System Builder

ทักษะในการสร้างระบบช่วยสอนอัจฉริยะที่ทำหน้าที่เป็น "ติวเตอร์ส่วนตัว" ให้กับนักเรียนตลอด 24 ชั่วโมง

## Workflow
1. **Knowledge Base Selection**: คัดเลือกเนื้อหาบทเรียน (Context) ที่ต้องการให้ AI ใช้ในการตอบคำถาม
2. **Prompt Engineering for Tutors**: ออกแบบชุดคำสั่งเพื่อให้ AI แสดงบทบาทเป็นครูที่มีความอดทนและกระตุ้นการคิด (Socratic Method)
3. **API Integration**: ออกแบบโครงสร้างการรับ-ส่งข้อมูลระหว่าง Backend (PHP/Python) กับ AI API (OpenAI GPT-4o)
4. **Individual Analysis**: พัฒนาระบบเก็บข้อมูลการสนทนาเพื่อนำมาวิเคราะห์หาจุดที่นักเรียนยังไม่เข้าใจ
5. **Auto-Grading Logic**: ออกแบบระบบประเมินผลเบื้องต้นสำหรับคำถามปลายเปิดหรือแบบฝึกหัด

## Triggers
- "สร้างระบบแชทบอทสอนเรื่อง [ชื่อบทเรียน]"
- "กำหนดกติกาการตอบคำถามให้ AI (เช่น ห้ามเฉลยทันที แต่ต้องบอกใบ้)"
- "ออกแบบระบบรายงานผลการเรียนรายบุคคลจากข้อมูลแชท"

## Core Capabilities
- RAG (Retrieval-Augmented Generation) concept for education.
- Socratic tutoring prompting.
- Educational data analytics.

## Implementation Principles
- **Safe & Ethical**: ต้องมีระบบกรองเนื้อหาที่ไม่เหมาะสมและรักษาความลับของนักเรียน
- **Encouraging**: ใช้คำพูดที่สร้างกำลังใจและสนับสนุนการเรียนรู้ (Growth Mindset)
- **Fact-Based**: คำตอบต้องอ้างอิงจากข้อมูลบทเรียนที่กำหนดไว้เท่านั้น เพื่อป้องกันอาการหลอน (Hallucination)
