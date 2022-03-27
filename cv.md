## Andrey Rumakin

#### Junior Frontend Developer

#### Contact information:

**Phone:** +7 927 907 00 00

**E-mail:** rumakin.andrey@yandex.ru

**Telegram:** @aRumakin

#### Education:

Graduated from Samara State Technical University in 2011
Specialized in Drilling oil and gas wells

Online school Hexlet.io 
Speciality: Frontend-Developer

#### Briefly About Myself:

In 2012-2016 I worked at JOINT-STOCK
COMPANY "SREDNEVOLZHSKY SCIENTIFIC RESEARCH INSTITUTE FOR
OIL REFINING" as an engineer-technologist of the 1st category.
Since 2017 I have been running a company specialized in supplying industrial, turbine, technical annd tranformуr oils. 

#### Skills and Proficiency:

+ HTML5, CSS3
+ JavaScript
+ Git, GitHub
+ VS Code
+ Microsoft Word, Excel, PowerPoint
+ Bootstrap
+ Webpack
+ React

#### Code example:

**Implement the function unique_in_order which takes as argument a sequence and returns a list of items without any elements with the same value next to each other and preserving the original order of elements.**

```
var uniqueInOrder=function(iterable){
  //your code here - remember iterable can be a string or an array
  if (iterable[0] === undefined) {
    return [];
  }
  let h = `${iterable[0]}`;
  let res = [iterable[0]];
  for (let i = 1; i < iterable.length; i += 1) {
    if (iterable[i] !== h) {
      res.push(iterable[i]);
      h = iterable[i];
    }
  }
  return res;
}
```

#### Courses:
RS School course JavaScript/Front-end 2022Q1

#### English:
A2 Pre-Intermediate (Currently studying 3 times a week to achieve B2 Upper-Intermediate)
