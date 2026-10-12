# Claude Code Hands-on Manual 🇹🇭

> **จากไอเดียสู่แอปที่ใช้งานได้จริง ด้วย Claude Code**
>
> คู่มือภาษาไทยแบบลงมือทำทีละขั้น (Step-by-Step) พร้อมภาพรวม Workflow ตัวอย่างคำสั่ง และ **Prompt ที่คัดลอกไปใช้งานได้** เหมาะสำหรับผู้เริ่มต้น นักศึกษา อาจารย์ เภสัชกร และผู้สนใจ AI-assisted / Agentic Coding

## 📖 อ่านคู่มือ

- **เปิดคู่มือแบบ HTML:** [index.html](./index.html)
- **ลิงก์สำหรับ GitHub Pages:** https://wirunw.github.io/claudecode/ _(จะใช้งานได้หลังเปิด GitHub Pages และเผยแพร่สำเร็จ)_

> คู่มือนี้อยู่ในไฟล์ `index.html` ซึ่งเปิดอ่านผ่านเว็บเบราว์เซอร์ได้ ไม่จำเป็นต้องติดตั้งโปรแกรมเพื่อ **อ่าน** คู่มือ แต่การทดลองตามขั้นตอนอาจต้องใช้บัญชีและเครื่องมือที่เกี่ยวข้อง

## 🧭 เนื้อหาภายใน

| หัวข้อ | สิ่งที่จะได้ฝึก |
| --- | --- |
| เริ่มต้น AI Coding และ Claude Code | แนวคิดและการเตรียมสภาพแวดล้อม |
| Prompt และ Project Context | เขียนคำสั่งที่ชัดเจน พร้อมจัดการ `CLAUDE.md` |
| Sub-agents, Skills และ Custom Commands | ออกแบบผู้ช่วยเฉพาะงาน เพิ่มความรู้ และสร้าง Workflow ใช้ซ้ำ |
| MCP (Model Context Protocol) | เชื่อม Claude Code กับเครื่องมือภายนอก |
| วางแผนแอป | เขียน PRD ออกแบบหน้าจอ และเลือก Tech Stack |
| พัฒนา Web App | ใช้ React, Vite และ Tailwind CSS สร้าง UI |
| Authentication และ Database | เชื่อม Supabase Auth / Database พร้อมแนวคิด Row Level Security (RLS) |
| GitHub และ Deployment | จัดเก็บเวอร์ชัน และเผยแพร่เว็บด้วย Vercel |
| ทดสอบและปรับปรุง | ตรวจสอบการทำงาน แก้ปัญหา และปรับปรุงแอปอย่างต่อเนื่อง |

**ตัวอย่างโครงงานหลัก:** QuickOrder — ระบบจัดการออร์เดอร์สำหรับผู้ขายออนไลน์ ตั้งแต่การวางแผนจนถึงการนำขึ้นใช้งาน

## 🚀 วิธีเริ่มต้น

1. เปิดไฟล์ [index.html](./index.html) หรือหน้า GitHub Pages (เมื่อเปิดใช้งานแล้ว)
2. เลือกหัวข้อที่ต้องการเรียนรู้
3. ทำตาม Flow ทีละขั้น และคัดลอก Prompt ตัวอย่างไปปรับใช้กับโปรเจกต์
4. ทดสอบผลลัพธ์ทุกครั้ง โดยเฉพาะก่อนเชื่อมบริการจริงหรือ Deploy

## 🌐 เปิด GitHub Pages สำหรับ Repository นี้

1. ไปที่ **Settings → Pages**
2. ใน **Build and deployment** เลือก **Deploy from a branch**
3. เลือก Branch **main** และ Folder **/(root)**
4. กด **Save** และรอ GitHub เผยแพร่เว็บไซต์

เมื่อเผยแพร่เสร็จ สามารถเปิดที่ **https://wirunw.github.io/claudecode/**

## 🔐 ข้อควรระวัง

- ห้าม Commit `.env` หรือ Secret / Service Role Key ขึ้น GitHub
- ใช้ Supabase RLS และตรวจสอบสิทธิ์ตามผู้ใช้จริงก่อนนำระบบขึ้นใช้งาน
- ตรวจสอบความถูกต้องของคำสั่งและเอกสารประกอบจากบริการเวอร์ชันปัจจุบัน
- ตรวจสอบ Code Diff และทดสอบระบบก่อนอนุมัติการเปลี่ยนแปลงหรือ Deploy
- หลีกเลี่ยงการใส่ข้อมูลผู้ป่วย ข้อมูลส่วนบุคคล หรือข้อมูลอ่อนไหวในเครื่องมือ AI โดยไม่มีการอนุญาตที่เหมาะสม

## 👨‍🏫 ผู้เรียบเรียงสื่อการเรียนรู้

**ดร.ภก.วิรุณ เวชศิริ (Dr. Wirun Wetsiri)**

สื่อประกอบการเรียนรู้เรื่อง AI-assisted coding และการพัฒนาแอปพลิเคชันด้วย Claude Code ในบริบทการศึกษาและการประยุกต์ใช้งาน

---

**Repository:** [wirunw/claudecode](https://github.com/wirunw/claudecode) · **Format:** Interactive HTML · **Language:** ไทย
