<!DOCTYPE html>
<html>
<head>
  <title>You've Been Rickrolled!</title>
</head>
<body>
  <h1>Click the button... if you dare 😏</h1>
  <button onclick="document.getElementById('rickAudio').play()">Surprise Me</button>

  <audio id="rickAudio">
    <source src="never-gonna-give-you-up.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>
</body>

