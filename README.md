<h1>SurakshaSathi - Dynamic Insurance Pricing</h1>

<p>SurakshaSathi is a full-stack platform that dynamically adjusts insurance premiums in real-time across five lines: Car, Flood, Travel, Health, and Life. Built with a React frontend and Python backend, it leverages live IoT-free data and machine learning risk models to optimize pricing, enhance risk management, and improve customer engagement.</p>

<h2>Table of Contents</h2>
<ul>
  <li>Features</li>
  <li>Tech Stack</li>
  <li>Data Sources</li>
  <li>Installation</li>
  <li>Usage</li>
  <li>Architecture</li>
  <li>Mobile App</li>
  
</ul>

<h2 id="features">Features</h2>
<ul>
  <li><strong>Dynamic Pricing:</strong> Rule-based and ML-driven premium adjustments in real-time.</li>
  <li><strong>Car Insurance:</strong> Driver score from GPS (speeding, braking, night driving),weather hazards.</li>
  <li><strong>Flood Insurance:</strong> Hourly rainfall data, official flood alerts to bump rates during high-risk periods.</li>
  <li><strong>Travel Insurance:</strong> Trip dates, destination safety (crime index, AQI), weather forecasts, transport multipliers.</li>
  <li><strong>Health Insurance:</strong> AQI exposure, BMI, steps, sleep data, pre-existing conditions for personalized premiums.</li>
  <li><strong>Life Insurance:</strong> Demographics, lifestyle, occupation risk, family history for annual recalculations.</li>
  <li><strong>Claim Verification:</strong> Uploaded document checks to validate claims in real-time.</li>
  <li><strong>Notifications:</strong> Instant alerts on premium dues and claim status.</li>
  <li><strong>Dashboard:</strong> Clean React UI with live rates, claim status, and history charts.</li>
</ul>

<h2 id="tech-stack">Tech Stack</h2>
<ul>
  <li><strong>Frontend:</strong> React</li>
  <li><strong>Backend:</strong> Python (Flask/FastAPI), Pandas, Scikit-learn</li>
  <li><strong>Database:</strong> MongoDB Atlas</li>
  <li><strong>Deployment:</strong> Render, Vercel</li>
</ul>

<h2 id="data-sources">Data Sources</h2>
<ul>
  <li>GPS Telemetry (App)</li>
  <li>Public Weather APIs</li>
  <li>Government Flood Alert Feeds</li>
  <li>Environmental Sensors (AQI, Rainfall)</li>
  <li>Security and Crime Index Services</li>
</ul>

<h2 id="installation">Installation</h2>
<ol>
  <li>Clone the repo: <code>git clone https://github.com/your-org/SurakshaSathi.git</code></li>
  <li>Navigate into the directory: <code>cd SurakshaSathi</code></li>
  <li>Build and run</li>
</ol>

<h2 id="usage">Usage</h2>
<p>After setup, register or log in. Choose an insurance line, enter relevant inputs (e.g., trip details, driving session), and view dynamic quotes. Submit claims and track status from the dashboard.</p>

<h2 id="architecture">Architecture</h2>
<ul>
  <li><strong>Data Ingestion Service:</strong> Collects and normalizes data and API feeds.</li>
  <li><strong>Risk Model Service:</strong> Hosts ML models for each insurance line.</li>
  <li><strong>Pricing Engine:</strong> Combines rule-based logic and ML predictions.</li>
  <li><strong>Notification Service:</strong> Sends updates via Mail.</li>
  <li><strong>Frontend Service:</strong> React SPA consuming backend APIs.</li>
</ul>

<h2 id="mobile-app">Mobile App</h2>
<p>Our <strong>SurakshaSathi Mobile App</strong> tracks drivers via GPS to calculate a comprehensive <em>Driver Score</em>. Key functionalities include:</p>
<ul>
  <li><strong>Harsh Braking Detection:</strong> Monitors sudden deceleration events and penalizes unsafe braking.</li>
  <li><strong>High Acceleration Monitoring:</strong> Captures rapid acceleration instances to assess aggressive driving.</li>
  <li><strong>Night-Time Driving Analysis:</strong> Logs driving behavior during low-light hours to adjust risk scoring.</li>
  <li><strong>Real-Time Score Updates:</strong> Continuously computes and displays the driver score in the app.</li>
  <li><strong>Insights & Tips:</strong> Provides feedback on improving driving habits to lower insurance premiums.</li>
</ul>

