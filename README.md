<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="file.css" />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.11.2/css/all.min.css"
    />
  </head>
  <body>
    <div class="timer">
      <div class="controls">
        <input id="duration" value="3" />
        <div>
          <button id="start"><i class="fas fa-play"></i></button>
          <button id="pause"><i class="fas fa-pause"></i></button>
        </div>
      </div>
      <svg class="dial">
        <circle
          fill="transparent"
          stroke="green"
          stroke-width="15"
          r="190"
          cx="0"
          cy="200"
          transform="rotate(-90 100 100)"
        />
      </svg>
    </div>

    <script src="timer.js"></script>
    <script src="app.js"></script>
  </body>
</html>
