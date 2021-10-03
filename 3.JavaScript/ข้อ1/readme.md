# Codecamp #10
1. Preechaya Teeravickasit
2. JavaScript : Lab 1 การตั้งชื่อตัวแปรที่ดี  
2.1 ให้ประกาศตัวแปรชื่อ human และ name
2.2 ใส่ชื่อตัวเองในตัวแปร name  
2.3 นำค่าที่อยู่ในตัวแปร name ไปใส่ให้ human  
2.4 เมื่อ console.log(human) ออกมาต้องเป็นชื่อตัวเอง

        let human;  
        let name;  
        name = 'Preechaya';  
        human = name;  
        console.log(human);  
        document.querySelector('.name').innerHTML = `console.log(human) = ${human}`