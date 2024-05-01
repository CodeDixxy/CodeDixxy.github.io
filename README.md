<!DOCTYPE html>
<html>
<head>
    <h1>My News Website</h1>
<head>
<body>
    <h2>Welcome to My News Website</h2>
    <p>Check out our latest article:</p>
    <h2><a href="/BasicWebDev/Online News Article.pdf">Latest News</a></h2>
    <p><a href="BasicWebDev/Online News Article.pdf" target="_blank">Download PDF</a></p>
    <p>For more news, visit our <a href="https://www.thedailyupside.com" target="_blank">external news source</a>.</p>
</body>
</head>
</head>
</html>  

<!DOCTYPE html>
<html>
<head>
    <h2>Product Comparison</h2>
</head>
<body>
    <table border="1">
        <caption>A vs B</caption>
        <tr>
            <th>Product</th>
            <th>Price</th>
            <th>Features</th>
        </tr>
        <tr>
            <td>Product A</td>
            <td>$100</td>
            <td rowspan="2">- Product A:
  - Lightweight design
  - Easy to assemble
  - Energy-efficient
- Product B:
  - Durable construction
  - Sleek and modern design
  - Enhanced safety features.</td>
        </tr>
        <tr>
            <td>Product B</td>
            <td>$120</td>
        </tr>
        <tr>
            <td colspan="3">Both products come with a 1-year warranty.</td>
        </tr>
    </table>
    <ul>
        <li>Product A is cheaper than Product B.</li>
        <li>Both products have similar features.</li>
        <li>Both products come with a 1-year warranty.</li>
    </ul>
</body>
</html>

<!-- Start of Math Test -->

<form>
  <label for="name">Name:</label><br>
  <input type="text" id="name" name="name"><br><br>
  
  <p>Multiple Choice Questions:</p>
  
  <p>1. What is the result of 5 + 3?</p>
  <input type="radio" id="q1a" name="q1" value="a">
  <label for="q1a">a) 7</label><br>
  <input type="radio" id="q1b" name="q1" value="b">
  <label for="q1b">b) 8</label><br>
  <input type="radio" id="q1c" name="q1" value="c">
  <label for="q1c">c) 6</label><br><br>
  
  <p>2. What is the square root of 25?</p>
  <input type="radio" id="q2a" name="q2" value="a">
  <label for="q2a">a) 5</label><br>
  <input type="radio" id="q2b" name="q2" value="b">
  <label for="q2b">b) 4</label><br>
  <input type="radio" id="q2c" name="q2" value="c">
  <label for="q2c">c) 6</label><br><br>
  
  <p>3. What is the result of 7 multiplied by 3?</p>
  <input type="radio" id="q3a" name="q3" value="a">
  <label for="q3a">a) 10</label><br>
  <input type="radio" id="q3b" name="q3" value="b">
  <label for="q3b">b) 21</label><br>
  <input type="radio" id="q3c" name="q3" value="c">
  <label for="q3c">c) 28</label><br><br>
  
  <p>Word Problem:</p>
  <p>Solve the following equation for x:</p>

  
  <p>Math Symbols:</p>
  <p>&sum; (Summation)</p>
  <p>&times; (Multiplication)</p>
  <p>&radic; (Square Root)</p><br>
  
  <input type="submit" value="Submit">
</form>

<!-- End of Math Test -->

<!DOCTYPE html>
<html>
<head>
  <title>Color Scheme Table</title>
  <style>
    table {
      width: 100%;
      border-collapse: collapse;
    }
    th, td {
      border: 1px solid black;
      padding: 8px;
      text-align: center;
    }
    th {
      background-color: #f2f2f2;
      font-family: Arial, sans-serif;
      font-weight: bold;
    }
    td {
      font-family: Arial, sans-serif;
    }
    .color-name {
      font-style: italic;
    }
    .color-sample {
      width: 50px;
      height: 50px;
    }
  </style>
</head>
<body>

<h1 style="font-family: Arial, sans-serif;">My Color Scheme</h1>

<table>
  <tr>
    <th>Color Name</th>
    <th>Hex</th>
    <th>RGB</th>
    <th>HSL</th>
  </tr>
  <tr>
    <td class="color-name">Red</td>
    <td class="color-sample" style="background-color: #ff0000;"></td>
    <td>rgb(255, 0, 0)</td>
    <td>hsl(0, 100%, 50%)</td>
  </tr>
  <tr>
    <td class="color-name">Green</td>
    <td class="color-sample" style="background-color: #00ff00;"></td>
    <td>rgb(0, 255, 0)</td>
    <td>hsl(120, 100%, 50%)</td>
  </tr>
  <tr>
    <td class="color-name">Blue</td>
    <td class="color-sample" style="background-color: #0000ff;"></td>
    <td>rgb(0, 0, 255)</td>
    <td>hsl(240, 100%, 50%)</td>
  </tr>
  <tr>
    <td class="color-name">Yellow</td>
    <td class="color-sample" style="background-color: #ffff00;"></td>
    <td>rgb(255, 255, 0)</td>
    <td>hsl(60, 100%, 50%)</td>
  </tr>
</table>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menus</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="menu breakfast">
        <h2>Breakfast</h2>
        <ul>
            <li>Eggs Benedict</li>
            <li>Pancakes with Maple Syrup</li>
            <li>Fruit Salad</li>
            <li>Smoked Salmon Bagel</li>
            <li>Orange Juice</li>
        </ul>
    </div>
    <div class="menu lunch">
        <h2>Lunch</h2>
        <ul>
            <li>Caesar Salad</li>
            <li>Grilled Chicken Sandwich</li>
            <li>Vegetable Soup</li>
            <li>Club Sandwich</li>
            <li>Iced Tea</li>
        </ul>
    </div>
    <div class="menu dinner">
        <h2>Dinner</h2>
        <ul>
            <li>Filet Mignon</li>
            <li>Grilled Salmon</li>
            <li>Roast Chicken</li>
            <li>Vegetable Stir-Fry</li>
            <li>Red Wine</li>
        </ul>
    </div>
    body {
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 100vh;
    background-color: #f0f0f0;
}

.menu {
    width: 400px;
    height: 550px;
    background-size: cover;
    color: white;
    padding: 20px;
    margin: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
}

.breakfast {
    background-image: url('breakfast.jpg');
    background-repeat: no-repeat;
    background-position: center;
}

.lunch {
    background-image: url('lunch.jpg');
    background-repeat: no-repeat;
    background-position: center;
}

.dinner {
    background-image: url('dinner.jpg');
    background-repeat: no-repeat;
    background-position: center;
}

h2 {
    text-align: center;
    margin-bottom: 20px;
}

ul {
    list-style-type: none;
    padding: 0;
}

li {
    margin-bottom: 10px;
}
</body>
</html>
