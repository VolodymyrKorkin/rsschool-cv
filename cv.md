# **KORKIN VLADIMIR**
## Front-end developer
### CONTACT ME
* GitHub: https://github.com/VolodymyrKorkin
* Telegram: @Vladimir_Korkin
* Discord: (@VolodymyrKorkin)
* Email: korkin.dev@gmail.com
### FOLLOW ME
* LinkedIn: https://www.linkedin.com/in/volodymyr-korkin/
* Facebook: https://www.facebook.com/KorkinVladimir
### SUMMARY
I started my career as an engineer 15 years ago from the beginning level. During these years I was learning a lot to develop my professional skills, to get new ones, to keep pace with the development of the industry. 
Last 5 years I was working as the Project’s Leading engineer in top construction companies. 
Technical development and programming, which are trending now,  always attracted me. Now I know exactly what I would like to devote my future career to and I'm keen to get knowledge in IT. This will allow me to obtain perspective profession and develop skills in programming. I really like to write code and I want to perfect in JavaScript and React.
### TECHNICAL SKILLS
* HTML, CSS
* Javascript, Python
* Git, VSCode
* PSDETCH, Figma 
### SAMPLE OF CODE
Create a Calculator constructor function that creates objects with three methods:
read() asks for two values ​​with prompt and stores their value in the properties of the object.
sum() returns the sum of the entered properties.
mul() returns the product of the input properties.
```javascript
function Calculator() {

  this.read = function() {
    this.firstNumber = +prompt('Введите первое число?', '0');
    this.secondNumber = +prompt('Введите второе число?', '0');	
  };

  this.sum = function() {
    return this.firstNumber + this.secondNumber;
  };

  this.mul = function() {
    return this.firstNumber * this.secondNumber;
  };
}

let calculator = new Calculator();
calculator.read();
```
