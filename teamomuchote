<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Para Mi Esposito</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: #ffe6e6;
      color: #333;
      text-align: center;
      margin: 0;
      padding: 0;
      position: relative;
      overflow: auto; /* Permitir desplazamiento */
    }
    h1 {
      color: #ff6666;
      font-size: 3em;
      margin-top: 50px;
    }
    p {
      font-size: 1.5em;
      margin: 20px;
    }
    .container {
      max-width: 800px;
      margin: auto;
      position: relative;
      z-index: 2;
    }
    footer {
      margin-top: 50px;
      font-size: 1em;
      color: #666;
    }
    .heart {
      position: absolute;
      width: 50px;
      height: 50px;
      background-color: #ff6666;
      transform: rotate(-45deg);
      animation: float 4s ease-in-out infinite;
      filter: brightness(1.2); /* Añadir brillo a los corazones */
    }
    .heart::before, .heart::after {
      content: '';
      position: absolute;
      width: 50px;
      height: 50px;
      background-color: #ff6666;
      border-radius: 50%;
      filter: brightness(1.2); /* Añadir brillo a los corazones */
    }
    .heart::before {
      top: -25px;
      left: 0;
    }
    .heart::after {
      top: 0;
      left: -25px;
    }
    @keyframes float {
      0% {
        transform: translateY(0) rotate(-45deg);
        opacity: 1;
      }
      50% {
        transform: translateY(-100px) rotate(-45deg);
        opacity: 0.7;
      }
      100% {
        transform: translateY(0) rotate(-45deg);
        opacity: 1;
      }
    }
    .love-images {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      margin-top: 20px;
    }
    .love-images img {
      width: 150px;
      height: auto;
      margin: 10px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3); /* Añadir sombra para más efecto */
      cursor: pointer; /* Cursor de mano para indicar interactividad */
      transition: transform 0.2s ease; /* Transición para el efecto de clic */
    }
    .love-images img:hover {
      transform: scale(1.1); /* Aumentar el tamaño de la imagen al pasar el ratón */
    }
    .flower {
      position: absolute;
      width: 50px;
      height: 50px;
      background-image: url('https://www.w3schools.com/w3images/flowers.jpg'); /* Imagen de flor */
      background-size: cover;
      animation: grow 2s ease-out forwards;
    }
    @keyframes grow {
      0% {
        transform: scale(0);
        opacity: 0;
      }
      100% {
        transform: scale(1);
        opacity: 1;
      }
    }
    /* Estilo para los botones */
    .love-question {
      margin: 30px 0;
    }
    .love-question button {
      padding: 10px 20px;
      font-size: 1.2em;
      margin: 10px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: transform 0.2s ease; /* Añadir transición al efecto de clic */
    }
    .btn-yes {
      background-color: #ff6666;
      color: white;
    }
    .btn-no {
      background-color: #666;
      color: white;
    }
    .btn-yes:hover {
      background-color: #ff4c4c; /* Efecto de cambio de color al pasar el ratón */
    }
    .btn-no:hover {
      background-color: #444; /* Efecto de cambio de color al pasar el ratón */
    }
    /* Estilo para el corazón grande */
    .big-heart-container {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      text-align: center;
      opacity: 0;
      transition: opacity 0.5s ease-in-out;
      z-index: -1;
    }
    .big-heart {
      width: 200px;
      height: 200px;
      background-color: #800020; /* Color vino */
      transform: rotate(-45deg);
      position: relative;
      margin: auto;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.3); /* Añadir sombra para brillo */
    }
    .big-heart::before, .big-heart::after {
      content: '';
      position: absolute;
      width: 200px;
      height: 200px;
      background-color: #800020; /* Color vino */
      border-radius: 50%;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.3); /* Añadir sombra para brillo */
    }
    .big-heart::before {
      top: -100px;
      left: 0;
    }
    .big-heart-text {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      font-size: 2em;
      color: #fff;
      z-index: 1;
    }
    .big-heart::after {
      top: 0;
      left: -100px;
    }
    .show-heart {
      opacity: 1;
      z-index: 10;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Para Mi Esposito</h1>
    <p>Mi querido Moshito,</p>
    <p>No hay palabras suficientes para expresar cuánto te amo. Cada día a tu lado es una bendición y me siento tan afortunada de tenerte en mi vida. Talvez no es la gran cosa amor pero me tomo tiempo jiji aqui aprendiendo informatica para hacerte este detallito.</p>
    <footer>
      <p>Con todo mi amor, Tu esposita Yazmin</p>
    </footer>

    <!-- Imágenes románticas -->
    <div class="love-images">
      <img src="https://plus.unsplash.com/premium_photo-1670078190212-6eef0486c931?q=80&w=1632&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Te Amo" data-message="¡Eres mi luz!">
      <img src="https://plus.unsplash.com/premium_photo-1674068281218-4e2c8e09deb3?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MjR8fGFtb3J8ZW58MHx8MHx8fDA%3D" alt="Eres Mi Vida" data-message="¡Eres todo para mí!">
      <img src="https://images.unsplash.com/photo-1516738824215-510471921590?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTIyfHxhbW9yfGVufDB8fDB8fHww" alt="Para Siempre" data-message="¡Nuestro amor sera para siempre!">
      <img src="https://images.unsplash.com/photo-1533158165527-63796a27c752?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8OTV8fGFtb3J8ZW58MHx8MHx8fDA%3D" alt="Mi Corazón" data-message="¡Tienes mi corazón mi esposito Beymar!">
    </div>

    <!-- Pregunta de amor -->
    <div class="love-question">
      <p>¿Me amas?</p>
      <button class="btn-yes">Sí</button>
      <button class="btn-no">No</button>
    </div>
  </div>
  <footer>
  <p>Debes amarme por siempre si? o Tu esposita Yazmin llorará</p>
  </footer>

  <!-- Contenedor del corazón grande y el texto -->
  <div class="big-heart-container">
    <div class="big-heart"></div>
    <div class="big-heart-text">¡Más te vale!</div>
  </div>

  <!-- Elemento de audio para el sonido de error -->
  <audio id="error-sound" preload="auto">
    <source src="error.mp3" type="audio/mpeg">
    <source src="error.wav" type="audio/wav">
    Tu navegador no soporta el elemento de audio.
  </audio>

  <script>
    const btnYes = document.querySelector('.btn-yes');
    const btnNo = document.querySelector('.btn-no');
    const bigHeartContainer = document.querySelector('.big-heart-container');
    const errorSound = document.getElementById('error-sound');

    // Funcionalidad del botón "No"
    btnNo.addEventListener('click', function() {
      errorSound.play(); // Reproducir sonido de error
      alert('¡Debes presionar "Sí"!');
    });

    // Funcionalidad del botón "Sí"
    btnYes.addEventListener('click', function() {
      bigHeartContainer.classList.add('show-heart');
      setTimeout(() => {
        bigHeartContainer.classList.remove('show-heart');
      }, 2000);
    });

    // Funcionalidad de los corazones flotantes al hacer clic en la pantalla
    document.addEventListener('click', function(event) {
      let heart = document.createElement('div');
      heart.className = 'heart';
      heart.style.left = (event.clientX - 25) + 'px'; // Centrar el corazón en el clic
      heart.style.top = (event.clientY - 25) + 'px'; // Centrar el corazón en el clic
      document.body.appendChild(heart);

      setTimeout(function() {
        heart.remove();
      }, 4000);
    });

    // Funcionalidad para mostrar mensajes bonitos al hacer clic en las imágenes
    const images = document.querySelectorAll('.love-images img');
    images.forEach(image => {
      image.addEventListener('click', function() {
        const message = this.getAttribute('data-message');
        alert(message);
      });
    });

    // Funcionalidad para mostrar flores al hacer clic en la pantalla
    document.addEventListener('click', function(event) {
      let flower = document.createElement('div');
      flower.className = 'flower';
      flower.style.left = (event.clientX - 25) + 'px'; // Centrar la flor en el clic
      flower.style.top = (event.clientY - 25) + 'px'; // Centrar la flor en el clic
      document.body.appendChild(flower);

      setTimeout(function() {
        flower.remove();
      }, 2000); // La flor desaparecerá después de 2 segundos
    });
  </script>
</body>
</html>
