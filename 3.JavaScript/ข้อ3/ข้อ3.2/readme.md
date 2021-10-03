# Codecamp #10
1. Preechaya Teeravickasit
2. JavaScript : Exercise ตัวแปรและประเภทของข้อมูล  
2.1 จงทำตามคำสั่งต่อไปนี้  
2.1.1 กำหนดตัวแปรสำหรับเก็บชื่อ และกำหนดค่าเริ่มต้นเป็นชื่อของผู้เรียน  
2.1.2 กำหนดตัวแปรสำหรับเก็บอายุ และกำหนดค่าเริ่มต้นเป็นอายุของผู้เรียน  
2.1.3 กำหนดตัวแปรสำหรับเก็บืที่อยู่ และกำหนดค่าเริ่มต้นเป็นที่อยู่ของผู้เรียน  
2.1.4 กำหนดตัวแปรสำหรับเก็บประวัติ ของผู้เรียนโดยใช้ตัวแปรทั้ง 3 ตัว ด้านบนประกอกอบการเขียนประวัติด้วย  


        let myName = 'Preechaya';  
        let myAge = 24;  
        let myAddress = 'Bangkok, Thailand';  
        let myHistory = 'My name is ' + myName + '. <br>' + 'I am ' + myAge + 'years old. <br>' + 'I live in ' + myAddress;  

        document.getElementById('p').innerHTML = `${myHistory}`;  