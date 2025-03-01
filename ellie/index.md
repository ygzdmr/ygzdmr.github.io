<style>
  /* --- General Reset and Base Styles --- */
  body {
    font-family: 'Open Sans', sans-serif; /* More modern, readable font */
    line-height: 1.6;
    color: #333;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4; /* Slightly off-white for better contrast */
  }

  *, *::before, *::after { /* Good practice for consistent box model */
    box-sizing: border-box;
  }

  /* --- Container --- */
  .container {
    max-width: 1100px; /* Wider container for larger screens */
    margin: 0 auto;
    padding: 20px;
    overflow: hidden; /* Clearfix for any floated elements */
  }

  /* --- Header --- */
  .header {
    text-align: center;
    padding: 60px 20px; /* More vertical padding */
    background-color: #fff; /* White background for contrast */
    border-bottom: 1px solid #eee;
    margin-bottom: 40px; /* Space between header and screenshot */
  }

  .header h1 {
    font-size: 3.5em; /* Larger heading */
    margin-bottom: 0.4em;
    color: #2980b9;
    font-weight: 700; /* Bolder heading */
  }

  .header p {
    font-size: 1.3em; /* Larger subheading */
    color: #555;
    max-width: 700px; /* Limit width for readability */
    margin: 0 auto; /* Center the paragraph */
  }

  /* --- Screenshot --- */
  .screenshot {
    text-align: center;
    margin: 40px 0 60px; /* More bottom margin */
  }

  .screenshot img {
    max-width: 100%; /* Fully responsive */
    height: auto;
    border-radius: 12px; /* Slightly larger radius */
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.15); /* More pronounced shadow */
    border: 1px solid #eee; /* Subtle border */
    display: block; /* Remove extra space below inline images */
    margin: 0 auto;  /* Center the image */
  }

  /* --- Features --- */
  .features {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); /* Wider minimum column width */
    gap: 30px; /* Larger gap */
    margin: 60px 0; /* More vertical margin */
  }

  .feature {
    padding: 30px; /* More padding */
    background-color: #fff; /* White background */
    border: 1px solid #eee;
    border-radius: 12px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.05); /* Subtle shadow for depth */
    transition: transform 0.2s ease, box-shadow 0.2s ease; /* Smooth hover effect */
  }

  .feature:hover {
    transform: translateY(-5px); /* Lift on hover */
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
  }

  .feature h3 {
    font-size: 1.7em; /* Larger heading */
    margin-bottom: 0.6em;
    color: #2980b9;
    font-weight: 600;
  }
    .feature p{
      font-size: 1.1rem;
    }

  /* --- Call to Action (CTA) --- */
  .cta {
    text-align: center;
    padding: 60px 20px;
    background-color: #2980b9; /* Use primary color for background */
    color: #fff;
    border-radius: 12px;
    margin-bottom: 40px; /* Space before footer */
  }

  .cta h2 { /* Added a heading to the CTA */
    font-size: 2.5em;
    margin-bottom: 1em;
    font-weight: 700;
  }

  .cta-button {
    display: inline-block;
    padding: 18px 36px; /* Larger button */
    background-color: #fff; /* White button */
    color: #2980b9; /* Primary color for text */
    text-decoration: none;
    border-radius: 8px; /* More rounded button */
    font-size: 1.3em;
    font-weight: 600;
    transition: background-color 0.3s ease, color 0.3s ease, transform 0.2s ease; /* Smooth transitions */
    border: 2px solid #fff; /* White border */
  }

  .cta-button:hover {
    background-color: #f0f0f0; /* Slight background color change */
    color: #1c6ea4; /* Darker blue on hover */
    transform: scale(1.05); /* Slightly enlarge on hover */
  }

  /* --- Footer --- */
  .footer {
    text-align: center;
    padding: 30px 20px; /* More padding */
    background-color: #fff; /* consistent with other sections */
    font-size: 0.9em;
    color: #777;
    border-top: 1px solid #eee;
  }

  .terms {
    margin-bottom: 15px; /* More space */
  }

  .terms a {
    color: #555;
    text-decoration: none;
    transition: color 0.3s ease;
  }

  .terms a:hover {
    color: #2980b9; /* Primary color on hover */
  }

  /* --- Responsive Adjustments (Media Queries) --- */
  @media (max-width: 768px) {
    .header h1 {
      font-size: 2.5em;
    }
    .header p {
      font-size: 1.1em;
    }
    .cta h2 {
      font-size: 2em;
    }
    .cta-button {
      padding: 15px 30px;
      font-size: 1.1em;
    }
        .features {
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); /* Adjust column width for smaller screens */
    }
  }
    @media (max-width: 480px) {
    .feature {
      padding: 20px; /* less padding inside features on small devices */
    }
  }

</style>

<div class="container">
  <div class="header">
    <h1>Ellie: Simple Habit Tracking</h1>
    <p>Build lasting habits, without the complexity.</p>
  </div>

  <div class="screenshot">
    <img src="{{ site.baseurl }}/ellie/images/screenshot.png" alt="Ellie App Screenshot">
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
    <h2>Ready to start building better habits?</h2>  <a href="YOUR_APP_STORE_LINK" class="cta-button">Download Now</a>
  </div>

  <div class="footer">
    <div class="terms">
      <a href="{{site.baseurl}}/ellie/terms">Terms of Use</a> - <a href="{{site.baseurl}}/ellie/privacy">Privacy Policy</a>
    </div>
    <p>&copy; 2025 Habib Yağız Demir. All rights reserved.</p>
  </div>
</div>
