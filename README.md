<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cat Choice</title>
  <style>
    /* Your CSS code */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      font-size: 62.5%;
    }

    body {
      background-color: #fff0f6;
      font-family: "Protest Riot", sans-serif;
    }

    .container {
      height: 100vh;
      margin: 0 auto;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }

    .cat-img {
      width: 30rem;
      height: 30rem;
      margin-bottom: 2rem;
    }

    .title {
      font-size: 3.6rem;
      color: #f53699;
      text-align: center;
      margin-bottom: 2rem;
    }

    .buttons {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: center;
      gap: 1rem;
    }

    .btn {
      padding: 1.5rem 2.5rem;
      border: none;
      border-radius: 4px;
      color: pink;
      font-size: 1.6rem;
      font-weight: 600;
      cursor: pointer;
      display: inline-block;
    }

    .btn--yes {
      background-color: #40c057;
    }

    .btn--no {
      background-color: #f03e3e;
    }

    .hidden {
      display: none;
    }
  </style>
</head>
<body>
  <div class="container">
    <img src="path-to-cat-image.jpg" alt="Cute cat" class="cat-img" />
    <h1 class="title">Do you like this cat?</h1>
    <div class="buttons">
      <button class="btn btn--yes">Yes</button>
      <button class="btn btn--no">No</button>
    </div>
  </div>
</body>
</html># galbut
