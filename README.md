<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Interactive Image Rating and Leaderboard System</title>
  <link rel="stylesheet" href="ratestyles.css">
</head>
<body>
  <div class="container">
    <h1>Vote for Your Favorite Image</h1>

    <!-- Image Voting Section -->
    <div class="image-boxes">
      <div class="image-box">
        <img id="imageA" src="" alt="Image A">
        <button id="voteA">Vote for A</button>
      </div>
      <div class="image-box">
        <img id="imageB" src="" alt="Image B">
        <button id="voteB">Vote for B</button>
      </div>
    </div>

    <!-- Leaderboard Section -->
    <h2>Leaderboard</h2>
    <table id="leaderboard">
      <thead>
        <tr>
          <th>Rank</th>
          <th>Image</th>
          <th>Score</th>
          <th>Ranking Score (E)</th>
        </tr>
      </thead>
      <tbody>
        <!-- Leaderboard entries will be dynamically added here -->
      </tbody>
    </table>
  </div>

  <!-- JavaScript -->
  <script src="version.js"></script>
</body>
</html>
