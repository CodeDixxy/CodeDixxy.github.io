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
    <p2><a href="BasicWebDev/BWD video step by step- blank.pdf" target="_blank">Download PDF</a></p2>
</html>
<!-- HTML -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <h1>Flashcard Review</h1>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1 class="title">Flashcard Review</h1>
    </header>
    <main>
        <section class="container">
            <article class="card">
                <h2 class="question">Who created the movie Cars?</h2>
                <p class="answer">Disney's Pixar</p>
            </article>
            <article class="card">
                <h2 class="question">What type of handwriting invloves one continuious stroke?</h2>
                <p class="answer">Cursive</p>
            </article>
            <!-- Add more cards here -->
            <article class="card">
                <h2 class="question">Who is the biggest sports brand in the world?</h2>
                <p class="answer">Nike</p>
            </article>
              <article class="card">
                <h2 class="question">What part of a car quites an exaust?</h2>
                <p class="answer">muffler</p>
            </article>
            <article class="card">
                <h2 class="question">What Anabloic Steriod was originally developed for the cattle industry but is now used by professional body builders?</h2>
                <p class="answer">Trenbalone Acetate</p>
            </article>
            <!-- Add more cards here -->
            <article class="card">
                <h2 class="question">What company created the Vision Pro?</h2>
                <p class="answer">Apple</p>
            </article>
              <article class="card">
                <h2 class="question">What is the most popular AI software?</h2>
                <p class="answer">ChatGPT</p>
            </article>
            <article class="card">
                <h2 class="question">What is the most popular luxury watch brand?</h2>
                <p class="answer">Rolex</p>
            </article>
        </section>
    </main>

</body>
</html>
<!DOCTYPE html>
<html>
  <body>
    <h1>Trading Stock Options and Crypto</h1>
    <p>This website provides an in-depth look at trading stock options and crypto. It covers the basics of what stock options and crypto are, common chart patterns and candle stick patterns, support and resistance, and trading indicators.</p>
    <h2>What is a stock option?</h2>
    <p>A stock option is a contract that gives the holder the right, but not the obligation, to buy or sell a specified amount of a particular stock at a predetermined price within a specified time period.</p>
    <p>There are two types of stock options: call options and put options.</p>
    <p>Stock options are traded on organized exchanges, such as the Chicago Board Options Exchange (CBOE) and the American Stock Exchange (AMEX).</p>
    <p>Advantages of trading stock options include the ability to hedge against potential losses, the ability to generate income through the sale of options, and the ability to speculate on the price movement of a stock without having to own the underlying stock.</p>
    <p>Disadvantages of trading stock options include the risk of losing the entire amount invested, the complexity of options trading, and the limited time frame for exercising the option.</p>
    <h2>What is crypto?</h2>
    <p>Crypto is a digital or virtual currency that uses cryptography for security. Crypto is decentralized, meaning it is not controlled by any government or financial institution.</p>
    <p>There are many different types of crypto, including Bitcoin, Ethereum, and Litecoin.</p>
    <p>Crypto is traded on online exchanges, such as Coinbase and Binance.</p>
    <p>Advantages of trading crypto include the potential for high returns, the ability to make anonymous transactions, and the decentralized nature of crypto.</p>
    <p>Disadvantages of trading crypto include the risk of losing the entire investment, the volatility of crypto prices, and the lack of regulation and protection for crypto investors.</p>
   <h2>Chart patterns and candle stick patterns</h2>
    <p>Chart patterns and candle stick patterns are visual patterns that can be used to predict the direction of the market.</p>
    <p>Two commonly used trading patterns for both stock options and cryptocurrencies are:

1. **Trend Following**:
   - This strategy involves identifying and following the prevailing market trend, whether it's upward (bullish) or downward (bearish).
   - Traders using this approach aim to capitalize on the momentum of the trend, buying when prices are rising (in an uptrend) or selling short when prices are falling (in a downtrend).
   - Technical analysis tools such as moving averages, trendlines, and momentum indicators like the Relative Strength Index (RSI) or Moving Average Convergence Divergence (MACD) are often used to confirm and identify trends.

2. **Support and Resistance Trading**:
   - Support and resistance levels are key areas on a price chart where buying or selling pressure is concentrated, respectively.
   - Traders using this strategy identify these levels and make trading decisions based on how the price behaves when it approaches them.
   - When the price approaches support, traders may look for buying opportunities, expecting the price to bounce back up. Conversely, when the price approaches resistance, traders may consider selling or shorting, anticipating a reversal.
   - Various technical analysis tools and chart patterns such as double tops, double bottoms, and head and shoulders patterns are used to identify support and resistance levels.

Candlestick patterns are widely used in technical analysis to help traders interpret price movements and make informed trading decisions. Here are some widely used candlestick patterns:

1. **Doji**:
   - A Doji candlestick pattern occurs when the opening and closing prices are very close to each other, resulting in a small or nonexistent body with long upper and lower wicks.
   - It suggests market indecision and potential reversal, especially when it forms after a strong trend.

2. **Hammer and Hanging Man**:
   - Hammer and Hanging Man patterns have small bodies with long lower wicks and little to no upper wick.
   - A Hammer forms after a downtrend and indicates potential bullish reversal, while a Hanging Man forms after an uptrend and signals potential bearish reversal.

3. **Engulfing Patterns**:
   - Bullish Engulfing: Occurs when a large bullish candlestick engulfs the previous smaller bearish candlestick. It suggests a bullish reversal.
   - Bearish Engulfing: Opposite of Bullish Engulfing, where a large bearish candlestick engulfs the previous smaller bullish candlestick, indicating a bearish reversal.

4. **Morning Star and Evening Star**:
   - Morning Star: Consists of three candlesticks - a large bearish candle, a small bullish or bearish candle with a gap down, and a large bullish candle that closes above the midpoint of the first candle. It indicates a bullish reversal.
   - Evening Star: The opposite of Morning Star, consisting of a large bullish candle, a small bullish or bearish candle with a gap up, and a large bearish candle that closes below the midpoint of the first candle. It signals a bearish reversal.

5. **Three White Soldiers and Three Black Crows**:
   - Three White Soldiers: Three consecutive long bullish candlesticks with higher closes suggest a strong uptrend continuation.
   - Three Black Crows: Three consecutive long bearish candlesticks with lower closes indicate a strong downtrend continuation.


These are just a few examples of widely used candlestick patterns. Traders often combine these patterns with other technical indicators and analysis techniques to confirm signals and improve their trading decisions. It's important to note that while candlestick patterns can provide valuable insights, they should always be used in conjunction with risk management strategies and an understanding of market context.
These trading patterns are widely used because they provide traders with structured approaches to analyzing price movements and making trading decisions. However, it's essential for traders to combine these patterns with risk management strategies and stay informed about market developments to improve their chances of success. Additionally, traders may also use fundamental analysis techniques, especially in stock trading, to complement their technical analysis.</p>
    <p>To use chart patterns and candle stick patterns, you need to be able to identify them on a chart and understand what they indicate about the market.</p>
  </body>
    </html>    
