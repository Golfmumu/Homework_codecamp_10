# Codecamp #10
1. Preechaya Teeravickasit
2. JavaScript : Exercise Arrow Function 
2.1 แปลง code ดังกล่าวเป็น Switch cases  

    // function ask(question, yes, no){  
    //     if(confirm(question)) yes()  
    //     else no();  
    // }  

    // ask(  
    //     "Do you agree?",  
    //     function() {alert("You agreed.");},  
    //     function() {alert("You canceled the execution.");}  
    // )  

        let ask = (question, yes, no) => {  
            if(confirm(question))  yes();  
            else no();  
        }  

        ask(  
            "Do you agree?",  
            function() {alert("You agreed.");},  
            function() {alert("You canceled the execution.");}  
        )  