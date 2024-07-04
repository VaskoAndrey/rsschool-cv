# Andrey Vasko
Energy Engineer

## Contacts for communication

* +375(29)2459039
* vasko.andrey2054@gmail.com

## Personal information

Date of Birth: 15/02/1999
Place of residence: Belarus, Grodno (relocation is possible).
Citizenship: Belarus.
Marital status: Not maried.

## Foreign languages

* Russian native 
* English А2 (Elementary)
* Polish А1 (Beginner)

## Education

2016 - 2021
Grodndno City University named after Yanka Kupala

Technical operation of power equipment of organizations
GPA: 8.36.

## Work experience

OJSC Belcard

* 08/2021 - 03/2022 Engineer
* 03/2022 - seens to present time Master of the compressor and pumping station

## Publications

Vasko A.V. SPECIFIC FEATURES OF PTL OPERATION // Scientific community of students of the XXI century. TECHNICAL SCIENCES: Sat. Art. by mat. LXXXIX intl. scientific-practical hairpin conf. No. 5(88). URL: https://sibac.info/archive/technic/5(88).pdf (date of access: 03/22/2021)
Vasko A.V. WAYS TO INCREASE THE ENERGY EFFICIENCY OF VENTILATION SYSTEMS // Scientific community of students of the XXI century. TECHNICAL SCIENCES: Sat. Art. by mat. C int. scientific-practical hairpin conf. No. 4(99). URL: https://sibac.info/archive/technic/4(99).pdf (date of access: 04/22/2021)

## Prof skills

* HTML, CSS, JavaScript
* vs code, basics of git
* Microsoft Office suite, confident PC user, Sketchup, Mathcad

## About myself

A young specialist in training, I aspire to change my profession and become a frontend developer, I need real experience in web development, no bad habits, conscientious, attentive, good memory, I strive for excellence.

## Completed tasks

* [Completed tasks](https://github.com/VaskoAndrey/LearnJS-tasks)
* [Codewars profile](https://www.codewars.com/users/VaskoAndrey2054)

## Example of code

**Description**

A Narcissistic Number is a positive number which is the sum of its own digits, each raised to the power of the number of digits in a given base. In this Kata, we will restrict ourselves to decimal (base 10).

For example, take 153 (3 digits), which is narcisstic:
    1^3 + 5^3 + 3^3 = 1 + 125 + 27 = 153

**Solution**

```
function narcissistic(value) {
  const arr = Array.from(new String(value));
  
  const narcNum = arr.reduce((sum, current) => sum + Math.pow(current, arr.length), 0);
  
  if(value == narcNum) {
    return true
  } else return false;
}
```

