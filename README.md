<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Self-Confidence Academy</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #d0dec9;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
    }

    .container {
      display: flex;
      background-color: white;
      max-width: 1000px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }

    .left {
      flex: 1;
    }

    .left img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
    }

    .right {
      flex: 1;
      background-color: #eeecec;
      padding: 40px;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }

    .right h1 {
      font-size: 2em;
      font-weight: normal;
      margin: 0 0 10px;
      color: #555;
    }

    .right h1 strong {
      display: block;
      font-weight: bold;
      color: #111;
    }

    .right p {
      margin-top: 30px;
      font-size: 0.95em;
      color: #333;
      text-transform: uppercase;
      letter-spacing: 1px;
    }

    @media (max-width: 768px) {
      .container {
        flex-direction: column;
      }

      .left, .right {
        width: 100%;
      }

      .right {
        padding: 20px;
        text-align: center;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="left">
      <img src="your-image.jpg" alt="Portrait" />
    </div>
    <div class="right">
      <h1>
        We don't build confidence –<br />
        <strong>We uncover it.</strong>
      </h1>
      <p>Self-Confidence Academy coming soon</p>
    </div>
  </div>
</body>
</html>
