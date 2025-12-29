<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">

  <!-- Mobile correctness -->
  <meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
  <meta name="apple-mobile-web-app-capable" content="yes">
  <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">

  <title>App</title>

  <style>
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      height: 100%;
      background: #ffffff;
      overflow: hidden;
      touch-action: manipulation;
    }

    iframe {
      position: fixed;
      inset: 0;
      width: 100vw;
      height: 100dvh; /* correct mobile viewport */
      border: none;
      display: block;
    }
  </style>
</head>

<body>

  <iframe
    src="https://script.google.com/macros/s/AKfycbwY3MPzCQsIfc5qJiD8rhfqdYKd_Ch9SMWvlhN_32jLQ8BtJ72sSDZrxmI-F9Ov8Vgqhw/exec"
    allowfullscreen>
  </iframe>

</body>
</html>
