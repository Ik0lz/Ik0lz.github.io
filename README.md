<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ROBLOX EXTERNALS & EXECUTORS</title>

  <style>
    body {
      background: linear-gradient(135deg, ##010101 0%, ##010101 100%);
      margin: 0;
      padding: 0;
      font-family: 'Roboto', sans-serif;
      color: white;
      overflow-x: hidden;
    }

    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
      text-align: center;
    }

    /* Estilo inspirado no "Let the WAVE begin" */
    h1 {
      font-size: 3.5rem;
      margin: 20px 0;
      color: white;
      font-weight: bold;
      font-style: italic;
      letter-spacing: 2px;
      text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.4);
    }

    h2 {
      font-size: 2.5rem;
      margin: 20px 0;
      color: #ff7e5f;
    }

    h3 {
      font-size: 1.8rem;
      margin: 10px 0;
      color: #feb47b;
    }

    .image-gallery {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-wrap: wrap;
      gap: 20px;
    }

    .scale-up {
      width: 250px;
      height: auto;
      transition: transform 0.4s ease, box-shadow 0.4s ease;
      border-radius: 10px;
      box-shadow: 0px 4px 15px rgba(0, 0, 0, 0.4);
    }

    .scale-up:hover {
      transform: scale(1.1) rotate(5deg);
      box-shadow: 0px 8px 25px rgba(255, 126, 95, 0.6);
    }

    .image-container {
      padding: 15px;
    }

    /* Estilização dos botões para ficar como os do site */
    .btn {
      background-color: white;
      color: #333;
      padding: 12px 20px;
      font-size: 1.2rem;
      border: none;
      border-radius: 25px;
      cursor: pointer;
      margin: 0 10px;
      font-weight: bold;
      transition: background-color 0.3s ease, transform 0.3s ease;
    }

    .btn:hover {
      background-color: #f1f1f1;
      transform: scale(1.05);
    }

    /* Responsivo */
    @media (max-width: 768px) {
      h1 {
        font-size: 2.5rem;
      }

      h2 {
        font-size: 2rem;
      }

      .scale-up {
        width: 200px;
      }
    }

    @media (max-width: 480px) {
      h1 {
        font-size: 2rem;
      }

      h2 {
        font-size: 1.5rem;
      }

      .scale-up {
        width: 150px;
      }
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>lol</h1>

    <div>
      <button class="btn">Download</button>
      <button class="btn">Get Key</button>
    </div>

    <h2>Externals</h2>
    <div class="image-gallery">
      <div class="image-container">
        <img src="https://github.com/user-attachments/assets/e7b72dd9-aee9-42af-9018-f87441d364f1" alt="MATRIX HUB" class="scale-up" />
      </div>
      <div class="image-container">
        <img src="https://github.com/user-attachments/assets/b95bc995-23d8-4910-9224-64be3f62cc2d" alt="DX9WARE" class="scale-up" />
      </div>
    </div>

    <h2>Executors</h2>
    <div class="image-gallery">
      <div class="image-container">
        <img src="https://github.com/user-attachments/assets/690499a1-d18b-4197-bb83-9d9d66556168" alt="WAVE" class="scale-up" />
      </div>
      <div class="image-container">
        <img src="https://github.com/user-attachments/assets/6852d8cf-cf0f-4cf9-9805-6001827696a3" alt="Celery" class="scale-up" />
      </div>
    </div>
  </div>

</body>
</html>
