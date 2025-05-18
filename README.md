# FocusFlow
simple website to help focusing while studying

Starting the work with a simple html page containing a head and a body (basic html components)

THE HEAD
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>FocusFlow | Study Helper</title>
  <link rel="stylesheet" href="style.css">
</head>

THE BODY
<body>
  <div class="container">
    <h1>FocusFlow 🚀</h1>
    
    <!-- Pomodoro Timer -->
    <div class="timer">
      <h2>Pomodoro Timer</h2>
      <div id="time">25:00</div>
      <button id="start-btn">Start</button>
      <button id="reset-btn">Reset</button>
    </div>

    <!-- To-Do List -->
    <div class="todo">
      <h2>Study Tasks</h2>
      <input type="text" id="task-input" placeholder="Add a task...">
      <button id="add-btn">Add</button>
      <ul id="task-list"></ul>
    </div>

    <!-- Motivational Quote -->
    <div class="quote">
      <p id="quote-text">"The expert in anything was once a beginner."</p>
    </div>
  </div>

  <script src="script.js"></script>
</body>
