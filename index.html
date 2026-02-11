<!DOCTYPE html>
<html>
  <head>
  <style>
    body {background: black;
      color: #00ff00;
      font-family: monospace;
      margin: 0;
      min-height: 100vh;}
  .terminal
    {max-width: 600px;
      margin: 40px auto;
      text-align: center;}
  h1 
    {font-family: monospace;
      margin: 0;
      font-size: 2em;}
  button
    {background: black;
     color: #00ff00;
     font-family: monospace;
     padding: 10px 16px;
     margin: 8px 0;
     cursor: pointer;}
  button:hover
    {background: #00ff00;
     color: black;}
    #output
  {max-width: 600px;
  margin: 20px auto;
  text-align: center;
  font-family: monospace;}
  #bar 
    {width: 300px;
      height: 20px;
      background: #00ff00;
      animation: countdown 30s linear forwards;}
@keyframes countdown {0%   { width: 300px; background: #00ff00;}
  66%  { width: 102px; background: #00ff00;}
  67%  { background: red; box-shadow: 0 0 10px red;}
  100% { width: 0%; background: red; }}
.trail {
  position: fixed;
  width: 6px;
  height: 6px;
  border: 1px solid #00ff00;
  pointer-events: none;
  opacity: 1;
  transition: opacity 0.6s linear, border-color 0.2s;}
.trail.fade { opacity: 0; }
body.panic .trail {
  border-color: red;
  animation: glitch 0.3s infinite;}
@keyframes glitch {
  0%   { transform: translate(0,0); }
  20%  { transform: translate(-2px,1px); }
  40%  { transform: translate(1px,-2px); }
  60%  { transform: translate(-1px,2px); }
  80%  { transform: translate(2px,-1px); }
  100% { transform: translate(0,0); }}
</style>
  </head>
   <body>
    <div class="terminal" id="terminal">
      <h1>ESCAPE</h1>
 <button onclick="doNotClick()">Do Not Click</button>
<button onclick="decryptFile()">Decrypt File</button>
<button onclick="hackMainframe()">Hack Mainframe</button>
<button onclick="launchSequence()">Launch Sequence</button>
<button onclick="disconnect()">Disconnect</button>
<button onclick="inspectLogs()">Inspect Logs</button>
<button onclick="callITSupport()">Call IT Support</button>
<button onclick="debugMode()">Debug Mode</button>
<button onclick="emergencyShutdown()">Shutdown</button>
<button onclick="redButton()">Press Red Button</button>
<button onclick="tryPassword()">Try Password</button>
    </div>
<div id="output"></div>
<p>TIME LEFT:</p>
<div id="bar"></div>
<script>
let alive = true;
const bar = document.getElementById("bar");
setInterval(() => {
  if (!alive) return;
  if (parseFloat(bar.style.width) <= 30) document.body.classList.add("panic");
}, 50);
document.addEventListener("mousemove", e => {
  if (!alive) return;
  const d = document.createElement("div");
  d.className = "trail";
  d.style.left = e.clientX + "px";
  d.style.top  = e.clientY + "px";
  document.body.appendChild(d);
  requestAnimationFrame(() => d.classList.add("fade"));
  setTimeout(() => d.remove(), 600);});
const output = document.getElementById("output");
const terminal = document.getElementById("terminal");
let step = 0;
setTimeout(() => {if (alive) {alive = false;
    document.getElementById("bar").style.animationPlayState = "paused";
    document.getElementById("output").innerHTML +=
      "<p>TIME EXPIRED.</p><p>SYSTEM LOCKED.</p>";}}, 30000);
const buttons = [
  "Inspect Logs",
  "Decrypt File",
  "Press Red Button",
  "Debug Mode",
  "Launch Sequence",
  "Try Password",
  "Do Not Click",
  "Hack Mainframe",
  "Call IT Support",
  "Shutdown",
  "Disconnect"];
const correctOrder = [
  "Inspect Logs",
  "Decrypt File",
  "Press Red Button",
  "Debug Mode",
  "Launch Sequence",
  "Try Password"];
function shuffleButtons() {
  const btnElements = terminal.querySelectorAll("button");
  let shuffled = [...buttons].sort(() => Math.random() - 0.5);
  btnElements.forEach((btn, i) => {
    btn.textContent = shuffled[i];
    btn.onclick = () => handleClick(shuffled[i]);});}
function printHint() {
  if(!alive) return;
  const hintMap = {
    0: "Inspect to get information.",
    1: "Files hide secrets.",
    2: "Red is never decorative.",
    3: "Systems need debugging.",
    4: "Prepare to launch.",
    5: "You know the password."};
  document.getElementById("output").innerHTML += "<p>" + hintMap[step] + "</p>";}
function handleClick(label) {if(!alive) return;
  if(label === correctOrder[step]) {step++;
    if(step === correctOrder.length) {output.innerHTML += "<p>ACCESS GRANTED. YOU ESCAPED.</p>";
    document.getElementById("bar").style.animationPlayState = "paused";
      alive = false;
      return;}
    shuffleButtons();
    printHint();} else {alive = false;
    document.getElementById("output").innerHTML += "<p>WRONG BUTTON.</p>";
    document.getElementById("output").innerHTML += "<p>SYSTEM LOCKED.</p>";
    document.getElementById("bar").style.animationPlayState = "paused";}}
shuffleButtons();
printHint();
</script>
  </body>
</html>
