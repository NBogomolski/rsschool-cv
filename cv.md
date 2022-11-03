# Nikita Bogomolski

## Getting in touch:

* Phone number: +375(29)994-21-68
* Email: nikbog03@gmail.com
* Telegram: @h1dd3nsk8er
* [LinkedIn](https://www.linkedin.com/in/nikita-bogomolski/ "My personal LinkedIn page")
* [fiverr](https://www.fiverr.com/h1dd3ngod?up_rollout=true)

## About me

Being a third year student of _Belarusian State University of Informatics and Radioelectronics_, I'm seeking to reach a goal of being hired to one of many IT companies in Belarus, since it is a common practice for students of my year. In order to achieve that I'm currently taking a course aside from university at **RS School**. As for my skills, I like to think I'm decent at English and a couple front-end technologies. My hobbies include skateboarding and playing the guitar. All in all, my top priority at the moment is getting the desired job.

## Skills

- HTML
- Cascading Style Sheets(CSS, SCSS)
- Programming Languages: 
    * JavaScript
    * Typescript(Beginner)
    * C Programming Language
    * Java
    * Pascal
- Git
- Frameworks: Angular
- Microsoft Office:
    * Microsoft Word
    * Microsoft Excel
- Design software (For web development):
    + Photoshop
    + Figma

## Code Example

```javascript
var productExceptSelf = function(nums) {
    let answer = [];
    let leftProd = [];
    let rightProd = [...nums];
    
    let prod = 1;
    for (let num of nums) {
        leftProd.push(prod);
        prod *= num;
    }
    
    prod = 1;
    for (let i = nums.length-1; i >= 0; i--) {
        rightProd[i] = prod;
        prod *= nums[i];
    }
    
    //merging
    for (let i in nums) {
        answer.push(leftProd[i]*rightProd[i]);
    }
    return answer;       
};
```

## Work Experience


## Education

- *Middle School #126 of Minsk* - Secondary Education
- *Belarusian State University of Informatics and Radioelectronics* - Bachelor's degree

## Languages

1. Russian
2. Belarusian
3. English
    * SOL Minsk - certificate of knowledge B2 (Intermediate), issued in May 2019
    * [EF Standart English Test](https://www.efset.org/cert/rYePGT "Certificate") - certificate of knowledge C2 (Proficient), issued in March 2022

