# Blog Requirements

### ภาพรวม
- เขียนโค้ดเพื่อดึงคอนเทนต์มาแสดงโดยเชื่อมต่อผ่านทาง REST API
- ตัวย่าง api ที่เปิดให้ใช้งานได้ฟรี (สามารถเลือกใช้ตัวอื่นได้): [https://jsonplaceholder.typicode.com/posts](https://jsonplaceholder.typicode.com/posts)/
- ส่งงานผ่านทาง Github repo ของตัวเอง

### 1) ฟีเจอร์ หน้า Home
- แสดงลิสต์บทความ 5 รายการ
- สามารถกดปุ่ม "แสดงเพิ่ม" เพื่อดึงบทความจาก API มาแสดงเพิ่มเติม
- สามารถคลิกที่ชื่อของแต่ละบทความเพื่อเข้าไปอ่านเนื้อหาของบทความดังกล่าวที่หน้า Blog Detail ได้
- สามารถพิมพ์ชื่อบทความในช่องค้นหาเพื่อฟิลเตอร์บทความที่มีชื่อตรงกัน

### 2) ฟีเจอร์ หน้า Blog Detail
- แสดงเนื้อหาของบทความที่คลิกเลือกจากหน้า Home
- คลิกกลับไปหน้า Home ได้

### Nuxt Commands

```bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).
