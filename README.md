# Andy.github.io
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dany - Portafolio</title>
  <link rel="stylesheet" href="style.css">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>

  <header>
    <h2>Dany.dev</h2>
  </header>

  <section class="profile">
    <img src="https://via.placeholder.com/120" class="avatar" alt="Tu foto">
    <h1>Dany</h1>
    <p class="subtitle">Creativo digital. Desarrollador Web. Comunicador visual.</p>
  </section>

  <div class="info">
    Disponible | <a href="#">Links</a> | Miembro desde 2023
  </div>

  <section class="content">
    <div class="card">
      <h2>¡Hola Mundo!</h2>
      <p>Bienvenido a mi portafolio personal donde comparto mis proyectos, ideas y recursos sobre desarrollo web y creatividad digital.</p>
      <img src="https://via.placeholder.com/600x300" alt="Imagen de portada">
    </div>

    <div class="card">
      <h2>Galería con solo CSS</h2>
      <p>Explora este efecto animado de galería con solo CSS. Mira el ejemplo interactivo en <a href="#">este artículo</a>.</p>
      <video controls width="100%">
        <source src="tu-video.mp4" type="video/mp4">
        Tu navegador no soporta este video.
      </video>
    </div>
  </section>

</body>
</html>

:root {
  --main-color: #ec008c;
  --background-color: #f5f5f5;
  --text-color: #333;
}

body {
  margin: 0;
  font-family: 'Inter', sans-serif;
  background-color: var(--background-color);
  color: var(--text-color);
}

header {
  background: var(--main-color);
  padding: 1rem;
  color: white;
  text-align: center;
}

.profile {
  text-align: center;
  margin-top: -50px;
}

.avatar {
  border-radius: 50%;
  width: 120px;
  border: 5px solid white;
}

h1 {
  margin: 0.5rem 0 0.2rem;
}

.subtitle {
  font-size: 0.95rem;
  color: #555;
}

.info {
  text-align: center;
  margin-top: 1rem;
  font-size: 0.9rem;
  color: #777;
}

.content {
  max-width: 700px;
  margin: 2rem auto;
  padding: 0 1rem;
}

.card {
  background: white;
  padding: 1.5rem;
  border-radius: 12px;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
  margin-bottom: 2rem;
}

.card img {
  max-width: 100%;
  border-radius: 12px;
}

.card video {
  border-radius: 12px;
  margin-top: 1rem;
}

a {
  color: var(--main-color);
  text-decoration: none;
}

