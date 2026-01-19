DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>LOCKED TERMINAL</title>
  <style>
    /* --------- CSS --------- */
    body {
      background-color: #000;
      color: #0f0;
      font-family: 'Courier New', monospace;
      margin: 0;
      padding: 20px;
    }

    h1 {
      text-align: center;
      color: #0ff;
      margin-bottom: 40px;
    }

    #game-text {
      white-space: pre-line;
      margin-bottom: 30px;
      line-height: 1.5em;
      font-size: 18px;
    }

    #choices button {
      background-color: #111;
      color: #0f0;
      border: 2px solid #0f0;
      padding: 10px 20px;
      margin: 5px;
      font-family: monospace;
      font-size: 16px;
      cursor: pointer;
    }

    #choices button:hover {
      background-color: #0f0;
      color: #000;
    }
  </style>
</head>
<body>
  <!-- Title -->
  <h1>LOCKED TERMINAL</h1>

  <!-- Text display -->
  <div id="game-text">
    ACCESS RESTRICTED.<br>
    Welcome to Terminal 7. Please choose an action.
  </div>

  <!-- Buttons will appear here -->
  <div id="choices"></div>

  <!-- --------- JavaScript --------- -->
  <script>
    // References
    const gameText = document.getElementById("game-text");
    const choicesDiv = document.getElementById("choices");

    // ---------- Step 4: Game State ----------
    let terminalState = "normal";   // normal, locked, unlocked
    let attempts = 0;
    let passwordFound = false;
    let secretUnlocked = false;
    let scanProgress = 0;

    // ---------- Step 5: Button creation ----------
    function createButton(text, onClickFunction) {
      const btn = document.createElement("button");
      btn.textContent = text;
      btn.addEventListener("click", onClickFunction);
      choicesDiv.appendChild(btn);
    }

    function updateChoices() {
      choicesDiv.innerHTML = "";
      if (terminalState === "normal") {
        createButton("Scan system", scanSystem);
        createButton("Guess password", guessPassword);
        createButton("Shut down", shutDown);
      }
    }

    // ---------- Actions ----------
    function scanSystem() {
      scanProgress++;

      if (scanProgress === 1) {
        gameText.textContent =
          "Scanning... Encrypted files detected. Possible password fragments found.";
      } 
      else if (scanProgress === 2) {
        gameText.textContent =
          "Deep scan complete. Password pattern resembles a date format.";
      } 
      else {
        passwordFound = true;
        gameText.textContent =
          "SCAN COMPLETE. PASSWORD RECOVERED: ACCESS GRANTED.";
      }
    }

    function guessPassword() {
      if (!passwordFound) {
        attempts++;
        gameText.textContent =
          "ACCESS DENIED. You don't have enough data yet.";

        if (attempts >= 3) {
          terminalState = "locked";
          gameText.textContent = "TERMINAL LOCKED. TOO MANY WRONG ATTEMPTS.";
          choicesDiv.innerHTML = "";
        }
        return;
      }

      terminalState = "unlocked";
      gameText.textContent = "PASSWORD ACCEPTED. TERMINAL UNLOCKED.";
      choicesDiv.innerHTML = "";
    }

    function shutDown() {
      gameText.textContent = "TERMINAL SHUTTING DOWN…";
      choicesDiv.innerHTML = "";
    }

    // ---------- Initialize game ----------
    updateChoices();
  </script>
</body>
</html>
