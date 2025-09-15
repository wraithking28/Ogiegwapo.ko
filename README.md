<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Always Be My Baby - David Cook</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <h1>Always Be My Baby</h1>
    <div class="image-wrapper">
      <img src="your-image.jpeg" alt="Collage of two friends" />
    </div>
    <div class="video-wrapper">
      <iframe width="560" height="315" src="https://www.youtube.com/embed/G3nWFr35e7I" 
        title="Always Be My Baby - David Cook (Lyrics)" frameborder="0" allowfullscreen>
      </iframe>
    </div>
    <p class="credit">Song by David Cook | Image by John</p>
  </div>
</body>
</html>

body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: linear-gradient(to right, #fceabb, #f8b500);
  color: #333;
  text-align: center;
}

.container {
  padding: 40px 20px;
}

h1 {
  font-size: 2.5em;
  margin-bottom: 20px;
  color: #5a2a83;
}

.image-wrapper img {
  max-width: 80%;
  height: auto;
  border-radius: 20px;
  box-shadow: 0 8px 16px rgba(0,0,0,0.3);
  margin-bottom: 30px;
}

.video-wrapper iframe {
  max-width: 100%;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.2);
}

.credit {
  margin-top: 20px;
  font-size: 0.9em;
  color: #555;
}

