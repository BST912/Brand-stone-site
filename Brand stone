<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Brand Stone Data Analytics</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }
    body {
      line-height: 1.6;
      background: #f5f7fa;
      color: #333;
    }
    header {
      background: #1a1a2e;
      color: #fff;
      padding: 2rem 1rem;
      text-align: center;
    }
    header h1 {
      font-size: 2.5rem;
    }
    header p {
      font-size: 1.2rem;
      margin-top: 0.5rem;
      font-style: italic;
    }
    section {
      padding: 2rem 1rem;
      max-width: 900px;
      margin: 0 auto;
    }
    h2 {
      color: #1a1a2e;
      margin-bottom: 1rem;
      font-size: 2rem;
    }
    .services ul, .testimonials ul {
      list-style: disc;
      margin-left: 1.5rem;
    }
    .image-banner {
      width: 100%;
      height: auto;
      display: block;
      margin: 0 auto 2rem auto;
      border-radius: 8px;
    }
    .testimonial, .case-study {
      background: #ffffff;
      padding: 1rem;
      border-left: 4px solid #1a1a2e;
      margin-bottom: 1rem;
      box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    }
    footer {
      background: #1a1a2e;
      color: #fff;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Brand Stone Data Analytics</h1>
    <p>Insight, Precision, Advantage</p>
  </header>

  <section>
    <img class="image-banner" src="https://source.unsplash.com/featured/?data,technology" alt="Data Analytics Image">
    <h2>About Us</h2>
    <p>We are a data analysis organization that offers expert solutions to small and medium-scale businesses. Our mission is to turn complex data into actionable insights, helping companies grow smarter and faster.</p>
  </section>

  <section class="services">
    <h2>Our Services</h2>
    <ul>
      <li>Data Cleaning & Preparation</li>
      <li>Exploratory Data Analysis</li>
      <li>Business Intelligence Dashboards</li>
      <li>Custom Reporting & Insights</li>
      <li>Predictive Analytics & Forecasting</li>
    </ul>
  </section>

  <section>
    <h2>Interactive Analytics</h2>
    <canvas id="dataChart" width="400" height="200"></canvas>
    <script>
      const ctx = document.getElementById('dataChart').getContext('2d');
      new Chart(ctx, {
        type: 'bar',
        data: {
          labels: ['Q1', 'Q2', 'Q3', 'Q4'],
          datasets: [{
            label: 'Client Growth (%)',
            data: [12, 19, 23, 35],
            backgroundColor: '#1a1a2e'
          }]
        },
        options: {
          responsive: true,
          scales: {
            y: {
              beginAtZero: true
            }
          }
        }
      });
    </script>
  </section>

  <section class="testimonials">
    <h2>Testimonials</h2>
    <div class="testimonial">
      <p><strong>Acme Retail Co.:</strong> "Brand Stone gave us real-time insights that completely changed our strategy. Our sales grew 25% in three months."</p>
    </div>
    <div class="testimonial">
      <p><strong>ByteWorks Ltd.:</strong> "Their custom dashboards are a game-changer. We now track KPIs daily with zero guesswork."</p>
    </div>
  </section>

  <section class="case-studies">
    <h2>Case Studies</h2>
    <div class="case-study">
      <h3>Retail Business Transformation</h3>
      <p>We helped a regional retail chain identify underperforming stores and optimize inventory. Result: 30% increase in revenue across 6 months.</p>
    </div>
    <div class="case-study">
      <h3>SaaS Analytics Dashboard</h3>
      <p>Created a tailored dashboard for a SaaS firm, enabling real-time user activity tracking. Increased customer retention by 18%.</p>
    </div>
  </section>

  <section>
    <h2>Contact Us</h2>
    <p>Email: contact@brandstonedata.com (placeholder)</p>
    <p>We're here to help you unlock the power of your data.</p>
  </section>

  <footer>
    <p>&copy; 2025 Brand Stone Data Analytics. All rights reserved.</p>
  </footer>
</body>
</html>
