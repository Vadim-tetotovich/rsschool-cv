# rsschool-cv
# Vadim Bondarchuk
## Contacts
* **Location:** Belarus
* **Phone:** +375 29 777-50-58
* **Email:** vadimbondarchuk10@gmail.com
* **GitHub:** Vadim-tetotovich
* **Vk id:** 229748358
## About me
I study at university and I want to become a front-end developer. I like to solve interesting tasks in the field of programming. I am a teamplayer, always ready to develop my skills and achieve my goals.
## Skills
* HTML
* CSS
* JS(Basic)
* C/C++
* C#
* Python(Basic)
## Code Example
```javascript
    function revrot(str, sz) {
    if(sz === 0) return ""
    const regSize = new RegExp('.{1,'+sz+'}', 'g')
    return str.match(regSize).map((digits) => {
      if(digits.length !== sz) {
        return ""
      }
      let sum = 0;
      for(let i = 0; i < digits.length; i++){
        sum += parseInt(digits[i]);
      }
      if(sum % 2 == 0){
        return digits.split("").reverse().join("")
      } else {
        return digits.slice(1) + digits[0];
      }
    }).join("")
}
```
## Experience
I have no work experienc.
## Education
* **University:** Belarusian State University Informatics and Radioelectronics
* **Courses:**
    * [FreeCodeCamp](https://www.freecodecamp.org/)
    * [Learn.javascript](https://learn.javascript.ru/)
## English
English level - A2
