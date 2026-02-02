<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dyno Sumo Robot - Autonomous Sumo</title>
<style>
/* ======================== COLORS ======================== */
:root {
  --bg-main: #0f1220;
  --bg-card: #171a2f;
  --bg-footer: #0a0c18;
  --text-main: #eaeaf0;
  --accent-primary: #8a9bff;
  --accent-gradient-start: #5b7cfa;
  --accent-gradient-end: #8a4fff;
}

body {
  margin: 0;
  font-family: 'Arial', sans-serif;
  background-color: var(--bg-main);
  color: var(--text-main);
  line-height: 1.6;
}

header {
  background: linear-gradient(135deg, var(--accent-gradient-start), var(--accent-gradient-end));
  text-align: center;
  padding: 60px 20px;
}
header h1 {
  font-size: 3rem;
  margin: 0;
}
header p {
  font-size: 1.2rem;
  opacity: 0.9;
}

section {
  max-width: 1000px;
  margin: 60px auto;
  padding: 0 20px;
}

h2 {
  color: var(--accent-primary);
  margin-bottom: 20px;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.card {
  background-color: var(--bg-card);
  padding: 20px;
  border-radius: 12px;
  box-shadow: 0 10px 25px rgba(0,0,0,0.3);
}

a {
  color: var(--accent-primary);
  text-decoration: none;
}

footer {
  background-color: var(--bg-footer);
  padding: 30px 20px;
  text-align: center;
  opacity: 0.8;
  font-size: 0.9rem;
}
</style>
</head>
<body>

<header>
  <h1>Dyno Sumo Robot</h1>
  <p>Autonomous Tactical Sumo Robot - Arduino Project</p>
</header>

<section>
  <h2>Project Overview</h2>
  <p>This project is an autonomous sumo robot that uses ultrasonic sensors and motor control to detect and engage an opponent. The system makes dynamic decisions based on opponent position, distance, and speed, allowing unpredictable tactical behavior.</p>
</section>

<section>
  <h2>Core Features</h2>
  <div class="grid">
    <div class="card">Three ultrasonic sensors for precise opponent detection (Left, Center, Right)</div>
    <div class="card">Full motor control with L298N driver</div>
    <div class="card">Dynamic attack, evade, and tactical behaviors</div>
    <div class="card">Speed and distance based decision-making logic</div>
  </div>
</section>

<section>
  <h2>Behaviors</h2>
  <div class="grid">
    <div class="card"><strong>Search:</strong> Rotate and scan patterns to locate opponent</div>
    <div class="card"><strong>Align:</strong> Adjust orientation for optimal attack</div>
    <div class="card"><strong>Attack:</strong> Aggressive forward and mixed attack routines</div>
    <div class="card"><strong>Tactical Attack:</strong> Retreat, pivot, and high-speed advance</div>
    <div class="card"><strong>Evade:</strong> Avoid collisions and high danger zones</div>
    <div class="card"><strong>Counter:</strong> Immediate response after evasion</div>
  </div>
</section>

<section>
  <h2>System Architecture</h2>
  <p>Sensors → Analysis → Decision Making → Motor Control. The architecture allows for future AI enhancements and a Finite State Machine for improved behavior management.</p>
</section>

<section>
  <h2>Full Arduino Code</h2>
  <p>The complete code of Dyno Sumo Robot is embedded below. Compatible for GitHub README code blocks without errors:</p>
  <pre><code>// Paste the entire Dyno Sumo Robot Arduino code here
// Ensure proper fixes for missing semicolons and byte assignments
// Example snippet:
byte M1_ENABLE = 3;
byte M1_FORWARD = 2;
byte M1_BACKWARD = 4;

// Then continue with the rest of your code...</code></pre>
</section>

<section>
  <h2>Applications</h2>
  <ul>
    <li>Autonomous Sumo Cmpetitions</li>
    <li>University Robotics Projects</li>
    <li>IEEE Robotics Teams</li>
    <li>Research in autonomous and behavior-based robotics</li>
  </ul>
</section>

<footer>
  <p>Dyno Sumo Robot © Autonomous Robotics Project | Designed with Dark Blue Theme</p>
</footer>

</body>
</html>
