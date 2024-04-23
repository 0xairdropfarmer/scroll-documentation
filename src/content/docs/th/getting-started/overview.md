---
section: gettingStarted
date: Last Modified
title: "ภาพรวมของ Scroll "
lang: "th"
permalink: "docs/conceptual-overview/"
excerpt: "ZK Rollups and Scroll"
whatsnext: { "User Guide": "/en/user-guide/", "Building on Scroll": "/en/developers/" }
---

## ยินดีต้อนรับสู่คู่มือการใช้งาน Scroll!!
 

Scroll คือ Ethereum  Layer 2 ที่มุ่งเน้นด้านความปลอดภัย  โดยใช้นวัตกรรมในการออกแบบการขยายขนาด และ zero knowledge proofs บน Ethereum. เครือข่าย Scroll สามารถเข้าถึงได้ง่ายขึ้น ตอบสนองได้เร็วขึ้น และรองรับผู้ใช้ได้มากกว่า ใช้งาน Ethereum เพียงอย่างเดียว หากคุณเคยใช้หรือพัฒนาแอปพลิเคชันบน Ethereum คุณจะรู้สึกคุ้นเคยกับ Scroll

## Scroll กำลังสร้างอะไรอยู่?

Scroll กำลังสร้างเทคโนโลยีเพื่อขยายขนาดให้กับ Ethereum

ในขณะที่ Ethereum เป็นเครือข่ายบล็อกเชนชั้นนำสำหรับการขับเคลื่อนแอปพลิเคชันกระจายอำนาจ แต่ความนิยมของมันก็นำมาซึ่งต้นทุนในการทำธุรกรรม ที่สูงขึ้น ส่งผลให้เป็นอุปสรรคต่อการเข้ามาใช้งานสำหรับผู้ใช้และนักพัฒนารุ่นต่อไป

โดยอาศัยงานวิจัยด้าน zero knowledge  ("zk") ชั้นแนวหน้า Scroll กำลังสร้างเครือข่าย Layer 2 rollup บน Ethereum  ในการร่วมมือแบบเปิดกับผู้อื่นในชุมชน Ethereum ได้สร้าง "zkEVM" ที่ทำให้ทุกกิจกรรมบนเครือข่ายซึ่งทำงานเช่นเดียวกับ Ethereum สามารถได้รับการรักษาความปลอดภัยด้วยสมาร์ทคอนแทรกต์ บน Ethereum เครือข่ายจะเผยแพร่ธุรกรรมทั้งหมดไปยัง Ethereum และ zkEVM จะสร้างและเผยแพร่ "proof" การเข้ารหัสลับว่าเครือข่าย Scroll กำลังปฏิบัติตามกฎของ Ethereum

ในที่สุด สัญญาอัจฉริยะของ Ethereum จะใช้ proof ยืนยันว่าทุกธุรกรรมบน Scroll เป็นธุรกรรมที่ถูกต้อง ทำให้เครือข่ายมีความปลอดภัย การกระจายอำนาจ และการต้านการเซ็นเซอร์อย่างมหาศาล ระดับความปลอดภัยและการขยายขนาดสำหรับ Ethereum เป็นไปได้เพียงด้วยการพัฒนาล่าสุดในด้านการเข้ารหัสลับแบบ zero knowledge การออกแบบโปรโตคอลบล็อกเชน และ การเร่งประสิทธิภาพของฮาร์ดแวร์


<!-- TODO: Confirm Architecture page exists -->
สำหรับข้อมูลเพิ่มเติมเกี่ยวกับสถาปัตยกรรมของเรา โปรดดู   [ที่โครงสร้างของ Scroll ](/technology/).

## สามารถใช้ Scroll ได้วันนี้หรือไม่?
เครือข่ายหลัก ของ Scroll บน Ethereum ได้เปิดตัวแล้ว! เรายังมี testnet ที่กำลังทำงานบน Ethereum Sepolia หรือที่เรียกว่า Scroll Sepolia testnet แม้ว่าเราจะมี [คู่มือที่ครอบคลุม](/user-guide/) แต่หากคุณคุ้นเคยกับการใช้ Ethereum คุณสามารถเริ่มต้นได้ภายในไม่กี่นาที 

- เข้าไปเยี่ยมชม [สะพานหลัก](https://scroll.io/bridge) หรือ [สะพานของ Scroll Sepolia ](https://sepolia.scroll.io/bridge) แล้วเชื่อมกระเป๋า
- ส่งโทเค็นจาก Ethereum mainnet ไปยัง Scroll  (หรือใช้ Scroll Sepolia  [faucet](/user-guide/faucet))
- ทดสอบ Scroll Sepolia testnet dapp เช่น [Uniswap Showcase](http://uniswap-showcase.sepolia.scroll.xyz/) ของเราหรือแม้แต่ [Aave](https://app.aave.com/) -- และแน่ใจว่าคุณได้เลือกเครือข่าย Scroll Sepolia แล้ว! 

## Scroll จะเดินหน้าไปทางใด?
เราได้เปิดตัว mainnet บน Ethereum แล้ว แต่ยังมีงานที่ต้องทำอีกมาก สิ่งต่อไปคือการกระจายอำนาจแต่ละองค์ประกอบของเครือข่าย หากต้องการติดตามข้อมูลล่าสุด โปรดดู[บล็อก](https://scroll.io/blog) ของเราหรือติดตามใน [Discord](https://discord.gg/scroll) หรือ [Twitter](https://twitter.com/scroll_zkp)  ของเรา

