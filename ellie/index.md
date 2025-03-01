<style>
  body {
    font-family: sans-serif;
    line-height: 1.6;
    color: #333;
    margin: 0; /* Remove default body margin */
    padding: 0;
  }
  .container {
    max-width: 960px;
    margin: 0 auto;
    padding: 20px;
  }
  .header {
    text-align: center;
    padding: 40px 0;
    background-color: #f8f8f8; /* Light gray background */
  }
  .header h1 {
    font-size: 3em;
    margin-bottom: 0.5em;
    color: #2980b9; /* Blue color for heading */
  }
  .header p {
    font-size: 1.2em;
    color: #555;
  }
  .screenshot {
    text-align: center;
    margin: 40px 0;
  }
  .screenshot img {
    max-width: 80%;
    height: auto;
    border-radius: 10px; /* Rounded corners */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Subtle shadow */
  }
  .features {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); /* Responsive grid */
    gap: 20px;
    margin: 40px 0;
  }
  .feature {
    padding: 20px;
    border: 1px solid #eee;
    border-radius: 10px;
  }
  .feature h3 {
    font-size: 1.5em;
    margin-bottom: 0.5em;
    color: #2980b9;
  }
  .cta {
    text-align: center;
    padding: 40px 0;
  }
  .cta-button {
    display: inline-block;
    padding: 15px 30px;
    background-color: #2980b9;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    font-size: 1.2em;
    transition: background-color 0.3s ease;
  }
  .cta-button:hover {
    background-color: #1c6ea4;
  }
  .footer {
    text-align: center;
    padding: 20px 0;
    background-color: #f8f8f8;
    font-size: 0.9em;
    color: #777;
  }
    .terms{
      margin-bottom: 10px;
    }
</style>

<div class="container">
  <div class="header">
    <h1>Ellie: Simple Habit Tracking</h1>
    <p>Build lasting habits, without the complexity.</p>
  </div>

  <div class="screenshot">
    <img src="{{ site.baseurl }}/images/screenshot.png" alt="Ellie App Screenshot">
  </div>

  <div class="features">
    <div class="feature">
      <h3>Track Anything</h3>
      <p>Monitor both the habits you want to build and the ones you want to break.</p>
    </div>
    <div class="feature">
      <h3>Flexible Scheduling</h3>
      <p>Set daily, weekly, or monthly goals.</p>
    </div>
    <div class="feature">
      <h3>Fully Customizable</h3>
      <p>Personalize each habit with colors, icons, goals, and units.</p>
    </div>
    <div class="feature">
      <h3>Powerful Reminders</h3>
      <p>Stay on track with customizable reminders.</p>
    </div>
      <div class="feature">
      <h3>Insightful Statistics</h3>
      <p>Visualize your progress with clear, interactive charts.</p>
    </div>
      <div class="feature">
      <h3>Privacy Focused</h3>
      <p>All data is stored locally on your device.</p>
    </div>
  </div>

  <div class="cta">
    <a href="YOUR_APP_STORE_LINK" class="cta-button">Download Now</a>
  </div>

  <div class="footer">
      <div class="terms">
        <a href="{{site.baseurl}}/terms.html">Terms of Use</a> - <a href="{{site.baseurl}}/privacy.html">Privacy Policy</a>
      </div>
    <p>&copy; 2023 Your Name/Company. All rights reserved.</p>
  </div>
</div>
