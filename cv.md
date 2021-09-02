# Rashid Zhumadilov
## Contacts 
* Address: Novosibirsk, Russia
* Phone: +7 (913) 204-55-19
* E-mail: fraust1337@gmail.com
* Github: https://github.com/roshik14 
## About
//

## Skills
* C/C# (basic knowledge)
* Javascript (basic knowledge)
* HTML/CSS (basic knowledge)
* Git

## Code examples
```javascript
function duplicateCount(text){
  let set = new Set();
  text = text.toLowerCase().split('').sort().join('');
  for (let i = 0; i < text.length; i++) {
    if (text[i] === text[i + 1]) {
      set.add(text[i]);
    }
  }
  return set.size;
  }
```
