---
name: iot-logic-architect
description: ออกแบบตรรกะการควบคุมอุปกรณ์ IoT และระบบวิเคราะห์ข้อมูลเซนเซอร์อัจฉริยะ (Edge Logic) พร้อมระบบแจ้งเตือนความผิดปกติ
---

# IoT Logic Architect

ทักษะในการออกแบบ "สมองกล" สำหรับอุปกรณ์ภาคสนาม เพื่อให้ระบบสามารถตัดสินใจและจัดการข้อมูลได้อย่างมีประสิทธิภาพและประหยัดพลังงาน

## Workflow
1. **Sensor & Data Mapping**: กำหนดประเภทของข้อมูล (pH, Temp, Humidity) และช่วงค่าปกติ (Threshold)
2. **Control Logic Design**: ออกแบบเงื่อนไขการทำงาน (If-Then-Else) เช่น การเปิด/ปิดปั๊มน้ำ หรือการปรับระดับแสง
3. **Anomaly Detection Strategy**: วางแผนการตรวจจับความผิดปกติและระบบการแจ้งเตือน (Alert System) ผ่านช่องทางต่างๆ (LINE, Email)
4. **Energy Optimization**: ออกแบบตรรกะเพื่อลดการใช้พลังงานในขณะที่ยังคงประสิทธิภาพการทำงานไว้
5. **Pseudo-code Generation**: จัดทำโครงสร้างตรรกะในรูปแบบ Pseudo-code หรือ Flowchart เพื่อให้นักพัฒนาเขียนโค้ด (C++/Python) ได้ง่ายขึ้น

## Triggers
- "ออกแบบตรรกะควบคุมสำหรับระบบ [ชื่อระบบ]"
- "กำหนดช่วงค่าวิกฤต (Critical Threshold) สำหรับ [เซนเซอร์]"
- "แนะนำวิธีประหยัดพลังงานสำหรับอุปกรณ์ IoT ชุดนี้"

## Core Capabilities
- Edge Computing logic design.
- Threshold-based automation.
- Anomaly detection and alerting systems.

## Implementation Principles
- **Reliability**: ระบบต้องทำงานได้อย่างเสถียรในทุกสภาวะ
- **Low Latency**: การตัดสินใจที่ Edge ต้องรวดเร็วเพื่อความปลอดภัยของระบบ
- **Maintainability**: โครงสร้างตรรกะต้องอ่านง่ายและแก้ไขได้สะดวก
