# placeyabet
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Place Ya Bet - Grant Kiser</title>
  <style>
    body {
      background-color: black;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      color: white;
      font-family: Arial, sans-serif;
      text-align: center;
    }
    h1 {
      cursor: pointer;
      font-size: 2rem;
      text-decoration: underline;
    }
    video {
      display: none;
      max-width: 90%;
      max-height: 80vh;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <h1 onclick="playVideo()">🎵 Place Ya Bet by Grant Kiser 🎵</h1>
  <video id="musicVideo" controls>
    <source src="PLACE_YOUR_VIDEO_URL_HERE.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>

  <script>
    function playVideo() {
      const vid = document.getElementById('musicVideo');
      vid.style.display = 'block';
      vid.play();
    }
  </script>
</body>
</html>
