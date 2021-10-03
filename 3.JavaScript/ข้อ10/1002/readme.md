# Codecamp #10
1. Preechaya Teeravickasit
2. JavaScript : Exercise Switch Cases 
2.1 แปลง code ดังกล่าวเป็น Switch cases  

    // let a = +prompt('a', '');  
    // console.log(typeof a);  

    // if (a == 0){  
    //     alert(0);  
    // }  
    // if (a ==1){  
    //     alert(1);  
    // }  
    // if (a == 2 || a == 3){  
    //     alert('2,3');  
    // }  

        let a = +prompt('a', '');  
        switch (a) {  
        case 0:  
            alert(0);  
            break;  

        case 1:  
            alert(1);  
            break;  
         
        case 2:  
        case 3:  
            alert('2,3');  
            break;  
    }