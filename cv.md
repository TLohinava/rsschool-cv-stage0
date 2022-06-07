# Tatsiana Lohinava
## Contact info
* [LinkedIn](https://www.linkedin.com/in/tatsiana-lohinava-a7312518a/)
* **Discord:** tandsympathy(@TLohinava)
## About me
Hi, I am a pediatrician-turned-developer, eager to learn, try out new stuff and experiment.
## Skills
* HTML
* CCS
* JavaScript
## What can I code for you?
It took me a couple of days to come up with a solution for [this here LeetCode problem](https://leetcode.com/problems/two-sum/) so why not to boast it?
```
var twoSum = function(nums, target) {
     let newArr =[];
    for(let j = 0; j < nums.length; j++) {
        let newNumber = target - nums[j];
           if(nums.indexOf(newNumber) > j) {
               newArr.push(j);
               newArr.push(nums.indexOf(newNumber));
               break;
           } else if (newNumber === nums[j]) {
               if (nums.indexOf(newNumber, j + 1) === -1){
                   continue;
               } else {
                   newArr.push(j);
                   newArr.push(nums.indexOf(newNumber, j + 1));
                   break;
               }
           }
    } return newArr;
}
```
## Portfolio
* My final projects for the IT-Academy course:
  + [Wooder](https://github.com/TLohinava/ITA_Final_assignment_Wooder)
  + [Lorem page](https://github.com/TLohinava/ITA_Final_assignment_Smile)
* Several small projects for the freeCodeCamp Responsive Web Design Course:
  + [Survey Form](https://codepen.io/tlohinava/pen/GRyOMKj)
  + [Tech documentation page](https://codepen.io/tlohinava/pen/MWQeVrr)
  + [Product Landing Page](https://codepen.io/tlohinava/pen/mdpXvpe)
## Education
* "Website development using HTML, CSS, JavaScript", IT Academy
* Udacity courses, such as *Intro to JavaScript, JavaScript and DOM, ES6, Object-Oriented JavaScript, etc.*
* edX *JavaScript Introduction* course
* freeCodeCamp *Responsive Web Design, JavaSCript Algorithms and Data Structures*
## Language skills
Fluent in English and German
