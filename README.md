<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ROBLOX EXTERNALS & EXECUTORS  </title>

  <style>
    body {
      background: linear-gradient(135deg, #1F1F1F, #1F1F1F);
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

    /* Estilo para a seção */
    .section {
      background-color: #1F1F1F;
      border: 2px solid rgba(255, 255, 255, 0.3); /* Borda branca transparente */
      border-radius: 10px;
      padding: 20px;
      margin: 20px 0;
    }

    /* Títulos */
    h1, h2, h3 {
      color: #7C7ABF; /* Cor roxa para todos os títulos */
      transition: color 0.3s ease;
    }

    h1:hover, h2:hover, h3:hover {
      color: #3731DF; /* Cor azul ao passar o mouse */
    }

    h1 {
      font-size: 3.5rem;
      margin: 20px 0;
      font-weight: bold;
      font-style: italic;
      letter-spacing: 2px;
      text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.4);
    }

    h2 {
      font-size: 2.5rem;
      margin: 20px 0;
    }

    h3 {
      font-size: 1.8rem;
      margin: 10px 0;
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
      transition: transform 0.4s ease, box-shadow 0.4s ease, filter 0.4s ease;
      border-radius: 10px;
      box-shadow: 0px 4px 15px rgba(0, 0, 0, 0.4);
    }

    .scale-up:hover {
      transform: scale(1.1) rotate(5deg);
      box-shadow: 0px 8px 25px rgba(255, 126, 95, 0.6);
      filter: brightness(0.8); /* Escurece a imagem ao passar o mouse */
    }

    .image-container {
      padding: 15px;
      transition: background-color 0.3s ease; /* Transição suave para o fundo */
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

    /* Efeito de cor ao passar o mouse sobre as imagens */
    .image-container:hover {
      background-color: #7C7ABF; /* Fundo roxo ao passar o mouse */
    }

    .image-container:hover .scale-up {
      filter: brightness(0.5); /* Escurece a imagem */
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
    <div class="section">
      <h1>Scripts: (For Executors):</h1>
      <div>
        <button class="btn">Infinite Yield</button>
        <button class="btn">Ring Parts V2</button>
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
        <div class="image-container">
          <img src="https://github.com/user-attachments/assets/df636c55-4241-4f82-a88b-bf3cec167129" alt="Solara" class="scale-up" />
        </div>
        <div class="image-container">
          <img src="https://github.com/user-attachments/assets/fadf41fe-3c30-4628-a03c-7ada98801e72" alt="Electron" class="scale-up" />
        </div>
      </div>
    </div>
  </div>

</body>
</html>
