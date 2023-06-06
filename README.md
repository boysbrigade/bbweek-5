bb-week5

Tasks: 
This week you need to add some more Javascipt to your website.

Task 1:
Create a simple calculator that can add two numbers.
Use the code below to set up 

```html
 <h1>Simple Calculator</h1>
  
  <label for="num1">Number 1:</label>
  <input type="number" id="num1">
  
  <label for="num2">Number 2:</label>
  <input type="number" id="num2">
  
  <button onclick="addNumbers()">Add</button>
  
  <p id="result"></p>
  
  <script>
    function addNumbers() {
      var num1 = parseFloat(document.getElementById("num1").value);
      var num2 = parseFloat(document.getElementById("num2").value);
      
      var sum = num1 + num2;
      
      document.getElementById("result").innerText = "Result: " + sum;
    }
  </script>
```
Task 2:
Change Background Color by press of the button. 
Using the code provide below make a three buttons that change the background colour

```html
  <h1>Change Background Color</h1>
  
  <button onclick="changeBackground('red')">Red</button>
  <button onclick="changeBackground('blue')">Blue</button>
  <button onclick="changeBackground('green')">Green</button>
  
  <script>
    function changeBackground(color) {
      document.body.style.backgroundColor = color;
    }
  </script>
```

