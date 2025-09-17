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
    #player {
      display: none;
      width: 80%;
      max-width: 800px;
      aspect-ratio: 16 / 9;
      margin-top: 20px;
      border: none;
    }
  </style>
</head>
<body>
  <h1 onclick="playVideo()">🎵 Place Ya Bet by Grant Kiser 🎵</h1>

  <!-- YouTube Embed Iframe (hidden until click) -->
  <iframe id="player"
    src=""
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen>
  </iframe>

  <script>
    function playVideo() {
      const player = document.getElementById("player");
      // Replace YOUTUBE_VIDEO_ID with your video's ID
      player.src = "https://www.youtube.com/embed/YOUTUBE_VIDEO_ID?autoplay=1";
      player.style.display = "block";
    }
  </script>
</body>
</html>
