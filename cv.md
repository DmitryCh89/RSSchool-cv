# Dmitry Chizhevsky

![myAvatar](/myAvatar.png)

discord: [dmitrych89](https://discord.gg/avWASeBk)

e-mail: <dmchizh89@gmail.com>

## About me:

I want to learn programming as a hobby and hope that the knowledge and skills I acquire will be sufficient for both my professional field and everyday life. Through studying programming, I aim to gain a better understanding of computer science. I chose JavaScript and frontend development due to their accessibility (the browser is the most accessible working environment for me).

## Skills:
* Proficient in Windows OS.
* Currently learning HTML, CSS, and JS.
* In the process of learning GIT.

## Code example:
``` js
function countPositivesSumNegatives(input) {
  let countPositives = 0;
  let sumNegatives = 0;
  
  if (input == [] || input == null) {
    return [];
  } else {
    for (let i = 0; i < input.length; i++) {
      if (input[i] == 0) {continue};
      if (input[i] > 0)  {countPositives++};
      if (input[i] < 0)  {sumNegatives += input[i]};
    }
    if (countPositives != 0 || sumNegatives != 0){
      return [countPositives, sumNegatives];
      } else {
      return [];
      }
  }
}
```

## Work Experience:

I have no experience in software development.

## Education:

* BSTU (Belarusian State Technological University), Chemical Technology Engineer.
* [RS School (JavaScript / Front-end Course, Pre-school)](https://rs.school/courses/javascript-preschool-ru) (ongoing).
* [MDN](https://developer.mozilla.org/ru/docs/Learn) Learning Area (ongoing).
* [freeCodeCamp](https://www.freecodecamp.org/learn) (ongoing).