# Kalinichenko Andrii

****************************************************************

## **Contacts:**
* Discord: 
* E-mail: kalinamono@gmail.com
* Tel: +3809687979958

#### **About myself:**

I learn in **RSScgool!**

### **Code Example:**

```
prm.addEventListener('click',e=>{
  console.log(arrForSelectCard);

  if(arrForSelectCard.length < 2 && e.target.className == 'flip-card-front'){
    arrForSelectCard.push(e.target.closest('div.flip-card').getAttribute('data-card'));
    open()
    checkOpen()

  }
  
    function checkOpen(){
      clickButton.push(e.target)
      if (arrForSelectCard.length == 2 &&  arrForSelectCard[0] != arrForSelectCard[1]) {

        setTimeout(() => {
          arrForSelectCard.length =0;
         clickButton.forEach(el=>{
          el.parentNode.classList.remove('active')
          console.log(el);
  
         })
        }, 1000);
        console.log(arrForSelectCard);
      }else if(arrForSelectCard.length ==2 &&  arrForSelectCard[0] == arrForSelectCard[1]){
        clickButton.length = 0
        arrForSelectCard.length = 0;
        
      }
    }

   function open(){
    if(arrForSelectCard.length !=2 && arrForSelectCard[0] ==arrForSelectCard[1]){
      console.log(1);
   }
   if(e.target.className =='flip-card-front'){
       e.target.parentNode.classList.toggle("active");
   }
   }
 
})
```

### **Work experiense:**
*Nothing yet*

### **Education and courses:**
1. CS50 video course
2. JS, CSS, HTML, Git video courses on YouTube channel Glo Academy
3. JavaScript https://learn.javascript.ru/
4. FreeCodeCamp Responsive Web Design https://www.freecodecamp.org
5. FreeCodeCamp JavaScript Algorithms and Data Structures https://www.freecodecamp.org

### **Language:**

English level - A2