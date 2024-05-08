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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Busy Day Schedule</title>
    <style>
        table {
            width: 80%;
            margin: 20px auto;
            border-collapse: collapse;
        }
        
        th, td {
            border: 1px solid #000;
            padding: 10px;
            text-align: center;
        }
        
        th {
            background-color: #f0f0f0;
        }
        
        .important {
            font-weight: bold;
        }
        
        .time {
            width: 20%;
        }
    </style>
</head>
<body>
    <h1>My Busy Day Schedule</h1>
    <table>
        <tr>
            <th>Time</th>
            <th>Event</th>
        </tr>
        <tr>
            <td class="time">08:00 AM</td>
            <td>Breakfast</td>
        </tr>
        <tr>
            <td class="time">09:00 AM</td>
            <td class="important">Work Meeting</td>
        </tr>
        <tr>
            <td class="time">11:00 AM</td>
            <td>Client Call</td>
        </tr>
        <tr>
            <td class="time">12:30 PM</td>
            <td>Lunch</td>
        </tr>
        <tr>
            <td class="time">02:00 PM</td>
            <td>Doctor's Appointment</td>
        </tr>
        <tr>
            <td class="time">04:00 PM</td>
            <td>Exercise</td>
        </tr>
        <tr>
            <td class="time">06:00 PM</td>
            <td>Dinner</td>
        </tr>
        <tr>
            <td class="time">08:00 PM</td>
            <td>Movie Night</td>
        </tr>
    </table>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Team Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Our Team</h1>
        <nav>
            <ul>
                <li><a href="#about">About Us</a></li>
                <li><a href="#services">Our Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <div class="team-member">
        <img src="member1.jpg" alt="Team Member 1">
        <div class="bio">
            <h2>Kelly Martha</h2>
            <p>Kelly Martha is a passionate graphic designer with over a decade of experience in creating visually stunning designs. With a keen eye for detail and a knack for creativity, Kelly has worked with various clients, ranging from small startups to large corporations. She believes that good design has the power to make a lasting impact and is dedicated to delivering top-notch design solutions that exceed expectations.</p>
        </div>
    </div>
    <div class="team-member">
        <img src="member2.jpg" alt="Team Member 2">
        <div class="bio">
            <h2>Jane Smith</h2>
            <p>Jane Smith is a skilled software engineer specializing in web development. With a strong background in programming languages such as HTML, CSS, and JavaScript, Jane has built numerous dynamic and user-friendly websites for clients across different industries. She is known for her problem-solving skills and ability to tackle complex coding challenges with ease. Jane is passionate about technology and is always eager to stay updated with the latest trends in web development.</p>
        </div>
    </div>
      <div class="team-member">
        <img src="member3.jpg" alt="Team Member 3">
        <div class="bio">
            <h2>Allan Bourne</h2>
            <p>Allan Bourne is a seasoned project manager with a proven track record of successfully leading teams and delivering projects on time and within budget. With excellent communication and organizational skills, Allan excels at coordinating team efforts, setting clear project goals, and overcoming obstacles along the way. His commitment to quality and dedication to client satisfaction have earned him praise from colleagues and clients alike.</p>
        </div>
    </div>
    <div class="team-member">
        <img src="member4.jpg" alt="Team Member 4">
        <div class="bio">
            <h2>Nick Write</h2>
            <p>Nick Write is a talented content writer known for his ability to craft engaging and informative content across various platforms. With a background in journalism and a passion for storytelling, Nick brings creativity and flair to every piece of writing he produces. Whether it's blog posts, articles, or social media content, Nick has a knack for capturing the attention of readers and delivering messages that resonate.</p>
        </div>
    </div>
      <!-- Add more team members as needed -->    
    <footer>
        <p>&copy; 2024 Our Company. All rights reserved.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Grid and Flexbox Puzzle Assignment</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="grid-container">
        <div class="name-section">Ryan Gaidis</div>
        <div class="puzzle-section">Selected Puzzle: Snowman</div>
        <div class="date-section">Assignment Date: May 1, 2024</div>
    </div>
    <div class="flex-container">
        <!-- Flex items (puzzle pieces) will be added dynamically using Flexbox -->
    </div>
    .grid-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    padding: 20px;
}

.flex-container {
    display: flex;
    flex-wrap: wrap;
}

.flex-item {
    width: 100px; /* Adjust according to puzzle piece size */
    height: 100px; /* Adjust according to puzzle piece size */
    background-color: #ddd; /* Placeholder color for puzzle pieces */
    margin: 5px; /* Adjust spacing between puzzle pieces */
}

.faulty-piece {
    display: none; /* Hide faulty puzzle piece */
}

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="scorecard_styles.css">
</head>
<body>
    <h1>Golf Scorecard</h1>
    <table class="scorecard">
        <tr>
            <th>Hole</th>
            <th>Par</th>
            <th>Player 1</th>
            <th>Player 2</th>
            <!-- Add more players if needed -->
        </tr>
        <tr>
            <td>1</td>
            <td>4</td>
            <td contenteditable="true"></td>
            <td contenteditable="true"></td>
        </tr>
        <!-- Add more rows for additional holes -->
    </table>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="scorecard_styles.css">
</head>
<body>
    <h1>Baseball Scorecard</h1>
    <table class="scorecard">
        <tr>
            <th>Inning</th>
            <th>Team 1</th>
            <th>Team 2</th>
        </tr>
        <tr>
            <td>1</td>
            <td contenteditable="true"></td>
            <td contenteditable="true"></td>
        </tr>
        <!-- Add more rows for additional innings -->
    </table>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="scorecard_styles.css">
</head>
<body>
    <h1>Bowling Scorecard</h1>
    <table class="scorecard">
        <tr>
            <th>Frame</th>
            <th>Player 1</th>
            <th>Player 2</th>
        </tr>
        <tr>
            <td>1</td>
            <td contenteditable="true"></td>
            <td contenteditable="true"></td>
        </tr>
        <!-- Add more rows for additional frames -->
    </table>
</body>
</html>
<html>
    <h2>How To Add a Video Onto YOUR Website!</h2>
    <p2><a href=""C:\Users\Ryan\Downloads\BWD video step by step- blank.pdf"" target="_blank">Download PDF</a></p2>
</html>
