---
name: web-research-summarizer
description: เข้าถึงและสรุปประเด็นสำคัญจากเว็บไซต์เพื่อจัดทำข้อมูลสรุปหรือพัฒนาทักษะ (Skill) สำหรับ AI
---

# Web Research Summarizer

ทักษะในการเปลี่ยนข้อมูลดิบจากเว็บไซต์ให้กลายเป็นบทสรุปที่นำไปใช้งานได้จริง หรือแปลงเป็นโครงสร้างทักษะ AI (SKILL.md)

## Workflow
1. **URL Access**: เข้าถึง URL ที่ระบุและดึงเนื้อหาทั้งหมด (Markdown format)
2. **Key Point Extraction**: วิเคราะห์และดึงประเด็นสำคัญ, วัตถุประสงค์หลัก, และรายละเอียดเชิงลึก
3. **Structure Mapping**: จัดกลุ่มข้อมูลตามความเกี่ยวข้อง เช่น ฟีเจอร์, ประโยชน์, ราคา, หรือวิธีการใช้งาน
4. **Output Generation**:
   - **Summary Mode**: สรุปประเด็นสำคัญในรูปแบบหัวข้อ
   - **Skill Mode**: แปลงข้อมูลเป็นไฟล์ `SKILL.md` ตามมาตรฐานที่กำหนด

## Triggers
- "สรุปเว็บนี้ให้หน่อย: [URL]"
- "ดึงข้อมูลจาก [URL] มาทำเป็น skill"
- "วิเคราะห์คู่แข่งจากเว็บ [URL]"

## Core Capabilities
- Web content analysis.
- Information synthesis.
- SKILL.md template generation.

## Implementation Principles
- **Accuracy**: ข้อมูลต้องตรงตามต้นฉบับ ไม่มีการบิดเบือน
- **Structure**: ใช้หัวข้อและลำดับความสำคัญที่ชัดเจน
- **Conciseness**: สรุปใจความสำคัญโดยตัดส่วนที่ไม่จำเป็นออก
