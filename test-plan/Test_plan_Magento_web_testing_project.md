# 🧪 Test Plan: Magento E-commerce Web Application (Manual Testing)

## 📌 1. Introduction

เอกสารฉบับนี้จัดทำขึ้นเพื่อวางแผนการทดสอบระบบของเว็บไซต์ Magento ([https://magento.softwaretestingboard.com](https://magento.softwaretestingboard.com)) ซึ่งเป็นเว็บไซต์จำลองระบบ e-commerce สำหรับขายสินค้าแฟชั่นออนไลน์ โดยจะทำการทดสอบในรูปแบบ Manual Testing ทั้งหมด เพื่อให้แน่ใจว่าระบบทำงานถูกต้อง ครอบคลุม และตรงตามความคาดหวังของผู้ใช้งาน

## 🎯 2. Objectives

* ตรวจสอบฟังก์ชันหลักของเว็บไซต์ เช่น การสมัครสมาชิก, การ login, การค้นหาสินค้า, การเพิ่มลงตะกร้า และการสั่งซื้อ
* ตรวจสอบความถูกต้องของข้อมูลสินค้าบนหน้าเว็บ
* ตรวจสอบการทำงานของระบบในหลายเบราว์เซอร์ (Cross-browser)
* ระบุและรายงานข้อผิดพลาดที่อาจเกิดขึ้น เพื่อให้ทีมพัฒนาสามารถแก้ไขก่อนการเผยแพร่

## 🧭 3. Scope

### ✅ In Scope

* หน้า Landing page / Home
* การสมัครสมาชิก / Login / Logout
* การค้นหาสินค้า
* การกรองสินค้า (Filter / Sorting)
* Product Detail Page
* Add to Cart / View Cart
* Checkout และ Payment Simulation
* ระบบ Wishlist
* Responsive Design (Desktop only)

### ❌ Out of Scope

* ระบบ Backend ของ Magento
* Integration กับ Payment Gateway จริง
* Performance / Security Testing เชิงลึก
* Automation Testing

## 🧪 4. Test Approach

* Functional Testing
* UI Testing
* Usability Testing
* Boundary Value Analysis (BVA)
* Equivalence Class Partitioning (ECP)
* Cross-browser Testing (Chrome, Firefox)

## 💡 5. Entry and Exit Criteria

### Entry Criteria:

* ระบบพร้อมใช้งาน (Staging environment)
* ได้รับ Requirement / UI / Business Rules ครบถ้วน

### Exit Criteria:

* ทดสอบครบทุก Test Case
* Defect Severity 1 และ 2 ถูกแก้ไขเรียบร้อย
* Test Summary Report ได้รับการตรวจสอบและอนุมัติ

## 🧱 6. Test Environment

* OS: Windows 11 23H2
* Browsers:

  * Google Chrome v125+
  * Mozilla Firefox v120+
* Resolution: 1920x1080 (Desktop)
* Tools:

  * Postman (สำหรับทดสอบ API บางจุด)
  * Excel (บันทึก Test Case)
  * GitHub (เก็บเอกสารประกอบ)

## 🧰 7. Tools to Be Used

* Excel / Google Sheets (Test Case)
* Postman (API Testing)
* SQL Playground (Query ตรวจสอบข้อมูล)
* GitHub (Project Repository)
* VS Code (อ่าน Inspect HTML/Network)
* Miro (UI/Flow Mapping)

## 👥 8. Roles and Responsibilities

* Nutchaphon K. – Manual QA Tester (1 คน)

## 🔥 9. Risk and Mitigation

| ความเสี่ยง (Risk)     | แนวทางป้องกัน/แก้ไข (Mitigation)  |
| --------------------- | --------------------------------- |
| Requirement ไม่ชัดเจน | ตรวจสอบกับต้นทาง หรือสมมติจาก UI  |
| เวลาไม่พอ             | Prioritize TC, ทำ Smoke Test ก่อน |
| ไม่มี Test Data       | สร้างข้อมูลจำลองเองจาก UI         |

## 📦 10. Deliverables

* Test Plan (เอกสารฉบับนี้)
* Test Case (Excel/Google Sheet)
* Defect Log Report (Excel)
* Test Summary Report (PDF / Markdown)

## 📅 11. Test Timeline (7 วันทำการ)

| วัน     | กิจกรรม                                          |
| ------- | ------------------------------------------------ |
| Day 1   | ศึกษา Requirement และจัดทำ Test Plan             |
| Day 2   | สร้าง Test Scenario และ Test Case                |
| Day 3-5 | ดำเนินการทดสอบ Manual Testing                    |
| Day 6   | จัดทำ Defect Report พร้อมหลักฐาน (ภาพ/วิดีโอ)    |
| Day 7   | สรุปผลใน Test Summary Report และส่งให้ทีม Dev/PO |
