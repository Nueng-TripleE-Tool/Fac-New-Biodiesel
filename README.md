# Fac. New Biodiesel — ISO 50001 Energy Tools

เครื่องมือประกอบระบบการจัดการพลังงาน ISO 50001:2018 ของ **บริษัท นิว ไบโอดีเซล จำกัด**
จัดทำโดย Triple E Technology Co., Ltd. (อ.หนึ่ง กลับทวี)

เว็บ: https://nueng-triplee-tool.github.io/Fac-New-Biodiesel/

## โครงสร้าง

| ที่ | เนื้อหา |
|---|---|
| `index.html` | หน้าแรกรวมการ์ดเครื่องมือ |
| `tools/` | เครื่องมือ HTML ไฟล์เดียว (ใช้งานออฟไลน์ได้ ไม่มี build step) |

## เครื่องมือ

| ไฟล์ | สาระ | เวอร์ชัน |
|---|---|---|
| `tools/Tool_NewBio_EnB_Production_Simulator.html` | จำลองไฟฟ้า/ความร้อน/พลังงานรวม/SEC รายกระบวนการจากแผนผลิต ด้วยสมการ EnB ส่วนที่ 1B (โรงสกัด, โรงกลั่น 1/2, Dry Fract., Bio3, โรงบรรจุ, ก๊าซชีวภาพ, EnB ทำนาย CPO Washing / Dry Fract. ส่วนขยาย) พร้อมผังการไหล ต้นทุน GHG และ JSON save/load | 1.0 (24 ก.ย. 2569) |

## ที่มาของสมการ

รายงานประเมินสมรรถนะเครื่องจักรและเส้นฐานพลังงาน ISO 50001 ปี 2569 Rev.1 (ตารางที่ 11.1) —
สร้างด้วย [EnMS_MLR_CUSUM_Dashboard](https://nueng-triplee-tool.github.io/energy-tools/tools/EnMS_MLR_CUSUM_Dashboard.html) ส่วนที่ 1B
จากข้อมูล NBD-* ปี 2568, โรงสกัดรายวัน ก.ค.–ส.ค. 2569 และรายงาน Power Plant Biogas ส.ค. 2569

> สมการอิงข้อมูลของโรงงานนี้เท่านั้น ใช้ได้ในช่วงข้อมูลที่สร้างสมการ ห้ามนำไปใช้กับโรงงานอื่นโดยไม่สร้างสมการใหม่
