1. การติดตั้ง Firebase ----------
$ npm install -g firebase-tools
--------------------------
2. สร้าง Folder และ Initial Firebase ----------
$ mkdir firebase_application
$ cd firebase_application
$ firebase init

**** ไม่ต้องตกใจนะครับถ้าหากเกิด Error และที่เกิด Error นี้ขึ้นเพราะว่าเรายังไม่ได้ Login Firebase *****
$ firebase login
มื่อพิมคำสั่ง firebase login มันจะถามเราก่อนว่า Allow Firebase to collect anonymous CLI usage information? อันนี้ขึ้นอยู่กับเราครับว่าเราจะอนุญาติให้ Firebase เก็บข้อมูลการใช้งานหรือไม่ หลังจากที่เลือกเสร็จแล้วก็จะมีหน้าเว็บเปิดขึ้นมาเพื่อให้เรา Login Google Accout ครับ เมื่อเรา Login เสร็จเรียบร้อยแล้ว Firebase ก็จะแสดง Permission ต่างๆที่ขอสิทธิ์เข้าถึงครับ หลังจากที่เสร็จก็พิมพ์ firebase init
$ firebase init
--------------------------
3. How to Deploy ----------
เปิด Terminal หรือ Git Bash
$ firebase deploy --only hosting




ที่มา : http://surl.li/oaxew