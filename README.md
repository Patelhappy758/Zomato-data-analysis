<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
 
</head>
<body>

  <h1>Zomato Data Analysis using Python</h1>
  <p>Understanding customer preferences and restaurant trends is important for making informed business decisions in the food industry. 
  This project analyzes Zomato’s restaurant dataset using Python to find meaningful insights.</p>

  <h2>Objectives</h2>
  <ul>
    <li>Do more restaurants provide online delivery compared to offline services?</li>
    <li>Which types of restaurants are most favored by the general public?</li>
    <li>What price range do couples prefer for dining out?</li>
  </ul>

  <h2>Project Overview</h2>
  <p>This project performs Exploratory Data Analysis (EDA) on the Zomato dataset to clean, process, and visualize restaurant data for valuable insights.</p>

  <h2>Libraries Used</h2>
  <ul>
    <li>Pandas</li>
    <li>NumPy</li>
    <li>Matplotlib</li>
    <li>Seaborn</li>
  </ul>

  <h2>Steps Involved</h2>
  <ol>
    <li><strong>Import Libraries:</strong> Use Pandas, NumPy, Matplotlib, and Seaborn.</li>
    <li><strong>Load Dataset:</strong> Read the Zomato dataset CSV file into a DataFrame.</li>
    <li><strong>Data Cleaning:</strong> Convert rating values to numeric and handle missing data.</li>
    <li><strong>Exploration:</strong> Analyze restaurant types, votes, online order availability, and price range.</li>
    <li><strong>Visualization:</strong> Use plots and charts to identify patterns and insights.</li>
  </ol>

  <h2>Key Insights</h2>
  <table border="1" cellspacing="0" cellpadding="6">
    <tr>
      <th>Aspect</th>
      <th>Observation</th>
    </tr>
    <tr>
      <td>Restaurant Type</td>
      <td>Dining restaurants dominate the dataset.</td>
    </tr>
    <tr>
      <td>Online Orders</td>
      <td>Most restaurants operate offline, but online ordering is growing.</td>
    </tr>
    <tr>
      <td>Ratings</td>
      <td>Most restaurants are rated between 3.5 and 4.0.</td>
    </tr>
    <tr>
      <td>Cost for Couples</td>
      <td>Preferred cost for two people is around ₹300.</td>
    </tr>
    <tr>
      <td>Ratings vs Orders</td>
      <td>Restaurants offering online orders tend to receive higher ratings.</td>
    </tr>
    <tr>
      <td>Type vs Order Mode</td>
      <td>Cafes get more online orders; dining restaurants rely on offline orders.</td>
    </tr>
  </table>

  <h2>Visualizations</h2>
  <ul>
    <li>Restaurant Type Distribution</li>
    <li>Votes by Restaurant Type</li>
    <li>Online vs Offline Orders</li>
    <li>Ratings Distribution</li>
    <li>Approximate Cost for Couples</li>
    <li>Ratings Comparison (Online vs Offline)</li>
    <li>Heatmap: Restaurant Type vs Order Mode</li>
  </ul>

  <h2>Conclusion</h2>
  <p>This analysis helps restaurant owners and data analysts understand customer behavior, optimize pricing, and improve service models. 
  It highlights that online ordering influences ratings positively, and cafes tend to attract more online customers compared to dining restaurants.</p>

  <h2>Project Structure</h2>
  <pre>
Zomato-Data-Analysis/
│
├── data/
│   └── Zomato-data-.csv
│
├── notebooks/
│   └── Zomato_Data_Analysis.ipynb
│
├── images/
│   ├── ratings_distribution.png
│   ├── online_vs_offline.png
│   └── heatmap.png
│
├── README.html
└── requirements.txt
  </pre>

  <h2>How to Run</h2>
  <ol>
    <li>Clone the repository:<br>
      <code>git clone https://github.com/Patelhappy758/Zomato-Data-Analysis.git</code>
    </li>
    <li>Navigate to the project directory:<br>
      <code>cd Zomato-Data-Analysis</code>
    </li>
    <li>Install required libraries:<br>
      <code>pip install -r requirements.txt</code>
    </li>
    <li>Run the notebook or script for analysis.</li>
  </ol>

  <h2>Author</h2>
  <p><strong>Happy Patel</strong><br>
  GitHub: <a href="https://github.com/Patelhappy758" target="_blank">Patelhappy758</a></p>

</body>
</html>
