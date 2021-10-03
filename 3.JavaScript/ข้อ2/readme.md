# Codecamp #10
1. Preechaya Teeravickasit
2. JavaScript : Lab การตั้งชื่อตัวแปรที่ดี  
2.1 ตั้งชื่อตัวแปรที่ใช้เก็บจำนวนเงินในกระเป๋าตังของคุณ  
2.2 ตั้งชื่อตัวแปรที่ใช้เก็บชื่อ ของพ่อและแม่คุณ  
2.3 ตั้งชื่อตัวแปรที่ใช้เก็บที่อยู่ของบ้านคุณ  
2.4 ตั้งชื่อตัวแปรที่ใช้เก็บอายุของจักรวาล


        let myMoney = 100;  
        let parentName = 'Teeravickasit';  
        let myAdress = 'Bangkok, Thailand';  
        let universeAge = '13770 mya';  

        document.querySelector('#p1').innerHTML = `There are ${myMoney} in my pocket.`  
        document.querySelector('#p2').innerHTML = `There are ${parentName} in my parent's name.`  
        document.querySelector('#p3').innerHTML = `I live in ${myAdress}.`  
        document.querySelector('#p4').innerHTML = `The universe is ${universeAge}.`  