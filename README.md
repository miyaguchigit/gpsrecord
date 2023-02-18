<!doctype html>
<html manifest="cache.manifest">
<html lang="en">

<head>
  <meta charset="utf-8">
  <title>GPS Tracker</title>
  <meta name="viewport"
        content="width=device-width, initial-scale=1">

  <link rel="stylesheet"
        href="style.css">
</head>

<body>

<header>
  <label>Track-Interval(ms)<input type="number" id="interval" value="100"></label>
  <button id="track-btn">Press to track</button>
  <button id="download"
          style="display: none">Download as JSON
  </button>
</header>

<br><br>
<label>Last 10</label>
<pre><code id="log"></code></pre>

<script src="track.js"></script>

</body>

</html>
