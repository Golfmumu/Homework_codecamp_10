# Codecamp #10
1. Preechaya Teeravickasit
2. JavaScript : Exercise Switch Cases 
2.1 แปลง code ดังกล่าวเป็น if-else statement  

    // switch (browser) {  
    //     case 'Edge':  
    //         alert( `You've got the edge` );  
    //         break;  
        
    //     case 'Chrome':  
    //     case 'Firefox':  
    //     case 'Safari':  
    //     case 'Opera':  
    //         alert(`Okay we support these browsers too`);  
    //         break;  
            
    //     default:  
    //         alert('We hope that this page looks ok !');  
    // }  
  
        let browser = prompt('What borowser does you use ?')  
        if( browser === 'Edge'){  
            alert(`You've got the edge`)  
        } else if (browser === 'Chrome' || browser === 'Firefox' || browser === 'Safari' || browser === 'Opera'){  
            alert(`Okay we support these browsers too`);  
        } else {
            alert('We hope that this page looks ok !');    
        }