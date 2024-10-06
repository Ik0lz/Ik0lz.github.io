<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ROBLOX EXTERNALS & EXECUTORS</title>

  <style>
    /* Background gradient and base styles */
    body {
      background: linear-gradient(135deg, #2A2727 0%, #3A3A3A 100%);
      margin: 0;
      padding: 0;
      font-family: 'Roboto', sans-serif;
      color: white;
      overflow-x: hidden; /* Prevent horizontal scroll */
    }

    /* General container style */
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
      text-align: center;
    }

    /* Title styling with gradient text effect */
    h1 {
      font-size: 3.5rem;
      margin: 20px 0;
      background: linear-gradient(90deg, #ff7e5f, #feb47b);
      background-clip: text;
      -webkit-background-clip: text;
      color: transparent;
      text-transform: uppercase;
      font-weight: bold;
      letter-spacing: 2px;
    }

    h2 {
      font-size: 2.5rem;
      margin: 20px 0;
      color: #ff7e5f;
    }

    /* Subtitle styling */
    h3 {
      font-size: 1.8rem;
      margin: 10px 0;
      color: #feb47b;
    }

    /* Flexbox for aligning images */
    .image-gallery {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-wrap: wrap;
      gap: 20px;
    }

    /* Image hover effect */
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

    /* Add some padding around images */
    .image-container {
      padding: 15px;
    }

    /* Button hover animation for future buttons if needed */
    .btn {
      background-color: #ff7e5f;
      color: white;
      padding: 12px 20px;
      font-size: 1.2rem;
      border: none;
      border-radius: 25px;
      cursor: pointer;
      transition: background-color 0.3s ease, transform 0.3s ease;
    }

    .btn:hover {
      background-color: #feb47b;
      transform: scale(1.05);
    }

    /* Responsive styling */
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
    <h1>ROBLOX EXTERNALS & EXECUTORS</h1>

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
      <div class="image-container">
        <img src="https://github.com/user-attachments/assets/df636c55-4241-4f82-a88b-bf3cec167129" alt="Solara" class="scale-up" />
      </div>
      <div class="image-container">
        <img src="https://github.com/user-attachments/assets/fadf41fe-3c30-4628-a03c-7ada98801e72" alt="Electron" class="scale-up" />
      </div>
    </div>
  </div>

</body>
</html>
