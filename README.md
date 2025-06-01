# revistalidi


 index.html

<link rel="stylesheet" href="styles.css">
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Revista Digital - Revista Lidi</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Mundo Actual</h1>
    <nav>
      <ul>
        <li><a href="#">Inicio</a></li>
        <li><a href="#">Tecnología</a></li>
        <li><a href="#">Cultura</a></li>
        <li><a href="#">Ciencia</a></li>
        <li><a href="#">Contacto</a></li>
        <li><a href="#">Medio Ambiente</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="destacado">
      <h2>Artículo Destacado</h2>
      <article>
        <img src="https://via.placeholder.com/800x300" alt="Artículo destacado">
        <h3>La inteligencia artificial en 2025</h3>
        <p>Exploramos los avances más recientes en IA y cómo están cambiando el mundo...</p>
        <a href="#">Leer más</a>
      </article>
    </section>

    <section class="articulos">
      <h2>Más artículos</h2>
      <div class="grid">
        <article>
          <img src="https://via.placeholder.com/400x200" alt="Artículo 1">
          <h3>Viajes espaciales accesibles</h3>
          <p>El turismo espacial ya no es solo ciencia ficción.</p>
          <a href="#">Leer más</a>
        </article>
        <article>
          <img src="https://via.placeholder.com/400x200" alt="Artículo 2">
          <h3>Arte digital y NFTs</h3>
          <p>Una revolución en la forma en que entendemos el arte.</p>
          <a href="#">Leer más</a>
        </article>
      </div>
    </section>
  </main>

  <footer>
 styles.css
    body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #b81010;
}

header {
  background-color: #fa0000;
  color: white;
  padding: 1rem;
}

header h1 {
  margin: 0;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 1rem;
  padding: 0;
}

nav a {
  color: white;
  text-decoration: none;
}

.destacado, .articulos {
  padding: 2rem;
  background-color: white;
  margin: 1rem auto;
  max-width: 1000px;
}

.grid {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
}

article {
  background: #fe0202;
  border: 1px solid #000000;
  padding: 1rem;
  flex: 1 1 45%;
}

article img {
  max-width: 100%;
  height: auto;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 1rem;
}
    <p>&copy; 2025 Mundo Actual. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
